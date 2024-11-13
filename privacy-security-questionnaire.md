# [Self-Review Questionnaire: Security and Privacy](https://w3ctag.github.io/security-questionnaire/)

> 01.  What information does this feature expose,
>      and for what purposes?

None. This specification is for a header that an origin outputs to the user agent, for optimizing page loading performance.

 * What information does your spec expose to the first party that the first party cannot currently easily determine: None.
 * What information does your spec expose to third parties that third parties cannot currently easily determine: None
 * What potentially identifying information does your spec expose to the first party that the first party can already access (i.e., what identifying information does your spec duplicate or mirror): None.
 * What potentially identifying information does your spec expose to third parties that third parties can already access: None.

> 02.  Do features in your specification expose the minimum amount of information
>      necessary to implement the intended functionality?

Yes. The feature only exposes the minimum required information, as a boolean header, to satisfy the use case.

> 03.  Do the features in your specification expose personal information,
>      personally-identifiable information (PII), or information derived from
>      either?

No. The feature does not relate to PII or any derived information thereof.

> 04.  How do the features in your specification deal with sensitive information?

No. The feature does not deal with sensitive information.

> 05.  Does data exposed by your specification carry related but distinct
>      information that may not be obvious to users?

This feature does not allow users to share data with origins.

> 06.  Do the features in your specification introduce state
>      that persists across browsing sessions?

No. The feature in the specification only applies to a single response and does not persist across browsing session.

> 07.  Do the features in your specification expose information about the
>      underlying platform to origins?

No.

> 08.  Does this specification allow an origin to send data to the underlying
>      platform?

No.

> 09.  Do features in this specification enable access to device sensors?

No.

> 10.  Do features in this specification enable new script execution/loading
>      mechanisms?

No.

> 11.  Do features in this specification allow an origin to access other devices?

No.

> 12.  Do features in this specification allow an origin some measure of control over
>      a user agent's native UI?

No.

> 13.  What temporary identifiers do the features in this specification create or
>      expose to the web?

None.

> 14.  How does this specification distinguish between behavior in first-party and
>      third-party contexts?

It does not differentiate.

> 15.  How do the features in this specification work in the context of a browser’s
>      Private Browsing or Incognito mode?

It does not differentiate.

> 16.  Does this specification have both "Security Considerations" and "Privacy
>      Considerations" sections?

No. The feature in the specification does not have any security or privacy impact.

> 17.  Do features in your specification enable origins to downgrade default
>      security protections?

No.

> 18.  What happens when a document that uses your feature is kept alive in BFCache
>      (instead of getting destroyed) after navigation, and potentially gets reused
>      on future navigations back to the document?

Nothing. The feature is only used during initial document processing.

> 19.  What happens when a document that uses your feature gets disconnected?

Nothing. The feature is only used during initial document processing.

> 20.  Does your feature allow sites to learn about the users use of assistive technology?
>

No.

> 21.  What should this questionnaire have asked?
>

Nothing else that comes to mind.