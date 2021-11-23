- Content Security Policy deals in HTTPS and prevents XSS (Cross Site Scripting).
- `Content-Security-Policy: script-src 'self'`
- `Content-Security-Policy-Report-Only: `: to debug
- `Content-Security-Policy: report-uri https://...`: uri that
violates the policy.

`
default-src: Define loading policy for all resources type in case of a resource type dedicated directive is not defined (fallback),

script-src: Define which scripts the protected resource can execute,

object-src: Define from where the protected resource can load plugins,

style-src: Define which styles (CSS) the user applies to the protected resource,

img-src: Define from where the protected resource can load images,

media-src: Define from where the protected resource can load video and audio,

frame-src: Define from where the protected resource can embed frames,

font-src: Define from where the protected resource can load fonts,

connect-src: Define which URIs the protected resource can load using script interfaces,

form-action: Define which URIs can be used as the action of HTML form elements,

sandbox: Specifies an HTML sandbox policy that the user agent applies to the protected resource,

script-nonce: Define script execution by requiring the presence of the specified nonce on script elements,

plugin-types: Define the set of plugins that can be invoked by the protected resource by limiting the types of resources that can be embedded,

reflected-xss: Instructs a user agent to activate or deactivate any heuristics used to filter or block reflected cross-site scripting attacks, equivalent to the effects of the non-standard X-XSS-Protection header,

report-uri: Specifies a URI to which the user agent sends reports about policy violation
`