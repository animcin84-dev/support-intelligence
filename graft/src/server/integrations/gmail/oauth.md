# src/server/integrations/gmail/oauth.ts

- required · function · L9-L13 — function required(name: "GOOGLE_CLIENT_ID" | "GOOGLE_CLIENT_SECRET" | "GOOGLE_REDIRECT_URI")
- stateSecret · function · L15-L19 — function stateSecret()
- OAuthStatePayload · interface · L21-L26 — interface OAuthStatePayload
- sign · function · L28-L30 — function sign(encoded: string)
- createOAuthState · function · L32-L41 — function createOAuthState(now = Date.now())
- validateOAuthState · function · L43-L70 — function validateOAuthState(state: string, cookieState: string | undefined, now = Date.now())
- buildOAuthAuthorizationUrl · function · L72-L82 — function buildOAuthAuthorizationUrl(state: string)
- TokenResponse · interface · L84-L90 — interface TokenResponse
- tokenRequest · function · L92-L108 — async function tokenRequest(body: URLSearchParams): Promise<TokenResponse>
- exchangeAuthorizationCode · function · L110-L118 — async function exchangeAuthorizationCode(code: string)
- refreshAccessToken · function · L120-L127 — async function refreshAccessToken(refreshToken: string)
- revokeGoogleToken · function · L129-L137 — async function revokeGoogleToken(refreshToken: string)
- fetchGmailProfileWithAccessToken · function · L139-L154 — async function fetchGmailProfileWithAccessToken(accessToken: string)
