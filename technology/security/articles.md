

## SCIM
* https://developers.onelogin.com/scim/create-app#connectscim

## Identity
* https://www.inkandswitch.com/backchannel/#
* http://www.erights.org/elib/capability/pnml.html
* https://wiki.p2pfoundation.net/Zooko%27s_Triangle

## OAuth Flows
* https://goteleport.com/blog/how-oidc-authentication-works/
* https://goteleport.com/blog/how-oauth-authentication-works/
* https://aaronparecki.com/oauth-2-simplified/#web-server-apps
* https://www.ge.com/digital/documentation/predix-services/IZjYwZTYzYTEtZjllYS00ZTA3LTliZWItZGQ5MDMyMmY1Yzk1.html

### API
* https://itnext.io/exposing-an-outsystems-rest-service-with-an-oauth-style-authorization-fded258cbe14
* https://stackoverflow.blog/2021/10/06/best-practices-for-authentication-and-authorization-for-rest-apis/

## Proxy ideas
* https://medium.com/codex/api-authentication-using-istio-ingress-gateway-oauth2-proxy-and-keycloak-a980c996c259

## Open Connect
* https://darutk.medium.com/understanding-id-token-5f83f50fa02e

### Testing
* https://jgurda.medium.com/how-to-mock-google-oauth2-api-in-three-easy-steps-28a908563c1e

## Zero Trust
* https://www.paloaltonetworks.com/cyberpedia/what-is-a-zero-trust-architecture
* https://magic-wormhole.readthedocs.io/en/latest/attacks.html

## Cryptography
* https://www.javamex.com/tutorials/cryptography/ciphers.shtml
* https://www.nayuki.io/page/native-hash-functions-for-java
* https://asecuritysite.com/encryption/whirl
* https://cryptobook.nakov.com/mac-and-key-derivation/hmac-and-key-derivation
* https://resources.infosecinstitute.com/topic/random-number-generation-java/ 
* https://www.valerionappi.it/brng-en/ - banana random number gen
* https://medium.com/asecuritysite-when-bob-met-alice/cybersecurity-medieval-witcraft-chimeras-and-the-hound-of-hades-cbac8bddecde
    * https://asecuritysite.com/digitalcert/ker

## OTP
* https://www.baeldung.com/spring-security-two-factor-authentication-with-soft-token
* https://stytch.com/docs/api/authenticate-otp
* https://privacyidea.readthedocs.io/en/latest/modules/api/validate.html#post--validate-check
* https://github.com/google/google-authenticator-android/blob/master/java/com/google/android/apps/authenticator/barcode/BarcodeCaptureActivity.java 
* https://kentcdodds.com/blog/how-i-built-a-modern-website-in-2021#authentication-with-magic-links - email links

## Google auth implementation
* https://github.com/google/google-authenticator-android/blob/6f65e99fcbc9bbefdc3317c008345db595052a2b/java/com/google/android/apps/authenticator/AuthenticatorActivity.java#L952
* https://github.com/google/google-authenticator-android/blob/6f65e99fcbc9bbefdc3317c008345db595052a2b/java/com/google/android/apps/authenticator/otp/CheckCodeActivity.java#L105
`"otpauth://hotp/issuer?secret=ABCDEFGHIJKLMNOP&algorithm=SHA1&digits=6&counter=8237&issuer=blah"`
 ```
final byte[] keyBytes = Base32String.decode(secret);
Mac mac = Mac.getInstance("HMACSHA1");
mac.init(new SecretKeySpec(keyBytes, ""));
PasscodeGenerator pcg = new PasscodeGenerator(mac);
return pcg.generateResponseCode(0L);
```

## Authorization
* https://medium.com/airbnb-engineering/himeji-a-scalable-centralized-system-for-authorization-at-airbnb-341664924574
* https://www.osohq.com/post/zanzibar
