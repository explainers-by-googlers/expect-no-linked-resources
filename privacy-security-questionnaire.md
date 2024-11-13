| 2.1. What information might this feature expose to Web sites or other parties, and for what purposes is that exposure necessary?

This feature is a Document-Policy header that an origin may choose to include in an HTTP resonse when it has no linked resources in the response, to indicate to the user agent that it may optimize resources required to conduct a speculative parse of the response. This will benefit the user in terms of reducing compute requirements on the client, and improve performance of the experience.

| 2.2. Do features in your specification expose the minimum amount of information necessary to enable their intended uses?

Yes. The feature only exposes the minimum required information as a boolean header, to satisfy the use case.

| 2.3. How do the features in your specification deal with personal information, personally-identifiable information (PII), or information derived from them?
Personal information is any data about a user (for example, their home address), or information that could be used to identify a user, such as an alias, email address, or identification number.

The feature does not relate to PII or any derived information thereof.

| 2.4. How do the features in your specification deal with sensitive information?
Personal information is not the only kind of sensitive information. Many other kinds of information may also be sensitive. What is or isn’t sensitive information can vary from person to person or from place to place. Information that would be harmless if known about one person or group of people could be dangerous if known about another person or group. Information about a person that would be harmless in one country might be used in another country to detain, kidnap, or imprison them.

The feature is unrelated to sensitive information.

| 2.5. Do the features in your specification introduce new state for an origin that persists across browsing sessions?

No. The feature in the specification only applies to a single response and does not persist across browsing session.

| 2.6. Do the features in your specification expose information about the underlying platform to origins?

No. The feature does not expose information about the underlying platform.

| 2.7. Does this specification allow an origin to send data to the underlying platform?

The specification only allows an origin to send a signal to the user agent on how to better handle the current response to achieve higher performance for the user experience.

| 2.8. Do features in this specification enable access to device sensors?

No.

| 2.9. Do features in this specification enable new script execution/loading mechanisms?

The specification enables a user agent to not attempt speculatively parsing the current response, or loading resources speculatively from it.

| 2.10. Do features in this specification allow an origin to access other devices?
If so, what devices do the features in this specification allow an origin to access?

No.

| 2.11. Do features in this specification allow an origin some measure of control over a user agent’s native UI?

No.

| 2.12. What temporary identifiers do the features in this specification create or expose to the web?

None.

| 2.13. How does this specification distinguish between behavior in first-party and third-party contexts?

Does not differentiate.

| 2.14. How do the features in this specification work in the context of a browser’s Private Browsing or Incognito mode?

No difference.

| 2.15. Does this specification have both "Security Considerations" and "Privacy Considerations" sections?

Feature in the specification does not have security or privacy impacts as it only indicates to the browser that there are no linked resources in a document.

| 2.16. Do features in your specification enable origins to downgrade default security protections?

The Document-Policy in the specification is an optional one, on both sides. The origin may avoid including it, and the browser may choose to ignore it.

| 2.17. How does your feature handle non-"fully active" documents?

Not applicable.

| 2.18. What should this questionnaire have asked?

None.