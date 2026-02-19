# [Self-Review Questionnaire: Security and Privacy](https://w3c.github.io/security-questionnaire/)

The full questionnaire is at https://w3c.github.io/security-questionnaire/.

---

01.  What information does this feature expose,
     and for what purposes?

A: The feature exposes the user's autofill information which corresponds to fields that already exist in the form about to be filled.
As such, it does not expose any new information that the document won't be exposed to (by reading the input field values) immediately after the event finished firing.

02.  Do features in your specification expose the minimum amount of information
     necessary to implement the intended functionality?

A: Yes.

03.  Do the features in your specification expose personal information,
     personally-identifiable information (PII), or information derived from
     either?

A: No PII is exposed that the user hasn't consented to exposing, and that won't be available to the document shortly after the event fired.

04.  How do the features in your specification deal with sensitive information?

A: There's no particular disctinction for sensitive information.

05.  Does data exposed by your specification carry related but distinct
     information that may not be obvious to users?

A: I don't believe so, beyond what browser autofill currently already does.

06.  Do the features in your specification introduce state
     that persists across browsing sessions?

A: No.

07.  Do the features in your specification expose information about the
     underlying platform to origins?

A: No.

08.  Does this specification allow an origin to send data to the underlying
     platform?

A: No.

09.  Do features in this specification enable access to device sensors?

A: No.

10.  Do features in this specification enable new script execution/loading
     mechanisms?

A: No.

11.  Do features in this specification allow an origin to access other devices?

A: No.

12.  Do features in this specification allow an origin some measure of control over
     a user agent's native UI?

A: No.

13.  What temporary identifiers do the features in this specification create or
     expose to the web?

A: None.

14.  How does this specification distinguish between behavior in first-party and
     third-party contexts?

A: There's no such distinction.

15.  How do the features in this specification work in the context of a browser’s
     Private Browsing or Incognito mode?

A: It works to the extent that autofill works in Incognito mode.

16.  Does this specification have both "Security Considerations" and "Privacy
     Considerations" sections?

A: no, it has a [single section covering both](https://wicg.github.io/autofill-event/#security-privacy).
17.  Do features in your specification enable origins to downgrade default
     security protections?

A: No.

18.  What happens when a document that uses your feature is kept alive in BFCache
     (instead of getting destroyed) after navigation, and potentially gets reused
     on future navigations back to the document?

A: Nothing.

19.  What happens when a document that uses your feature gets disconnected?

A: Nothing.

20.  Does your spec define when and how new kinds of errors should be raised?

A: No new errors should be raised.

21.  Does your feature allow sites to learn about the user's use of assistive technology?

A: No.

22.  What should this questionnaire have asked?

A: Nothing in particular.
