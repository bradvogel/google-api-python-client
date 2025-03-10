# Changelog

### [1.8.3](https://www.github.com/googleapis/google-api-python-client/compare/v1.8.2...v1.8.3) (2020-05-01)


### Bug Fixes

* downgrade repetitive logging calls to debug ([#885](https://www.github.com/googleapis/google-api-python-client/issues/885)) ([3bf2781](https://www.github.com/googleapis/google-api-python-client/commit/3bf2781e29cb828409f3a8a21939323286524569)), closes [#781](https://www.github.com/googleapis/google-api-python-client/issues/781)

### [1.8.2](https://www.github.com/googleapis/google-api-python-client/compare/v1.8.1...v1.8.2) (2020-04-21)


### Bug Fixes

* Remove `apiclient.__version__` ([#871](https://www.github.com/googleapis/google-api-python-client/issues/871)) ([c7516a2](https://github.com/googleapis/google-api-python-client/commit/1d8ec6874e1c6081893de7cd7cbc86d1f6580320d)), closes [googleapis#870](https://www.github.com/googleapis/googleapis/issues/870)


### [1.8.1](https://www.github.com/googleapis/google-api-python-client/compare/v1.8.0...v1.8.1) (2020-04-20)


### Bug Fixes

* Adding ConnectionError to retry mechanism ([#822](https://www.github.com/googleapis/google-api-python-client/issues/822)) ([c7516a2](https://www.github.com/googleapis/google-api-python-client/commit/c7516a2ea2c229479633690c109f8763dc0b30ed)), closes [googleapis#558](https://www.github.com/googleapis/googleapis/issues/558)
* replace '-' in method names with '_' ([#863](https://www.github.com/googleapis/google-api-python-client/issues/863)) ([8ed729f](https://www.github.com/googleapis/google-api-python-client/commit/8ed729f1d868a8713ab442bf0bf59e77ba36afb6))

### v1.8.0
  Version 1.8.0

  Release to support API endpoint override.

  New Features
  - Add api endpoint override. ([#829](https://github.com/googleapis/google-api-python-client/pull/829))

  Implementation Changes
  - Don't set http.redirect_codes if the attr doesn't exist and allow more httplib2 versions. ([#841](https://github.com/googleapis/google-api-python-client/pull/841))

### v1.7.12
  Version 1.7.12
  
  Bugfix release
  
  Implementation Changes
  - Look for field 'detail' in error message. ([#739](https://github.com/googleapis/google-api-python-client/pull/739))
  - Exclude 308s from httplib2 redirect codes list ([#813](https://github.com/googleapis/google-api-python-client/pull/813))
  
  Documentation 
  - Remove oauth2client from docs ([#738](https://github.com/googleapis/google-api-python-client/pull/738))
  - Fix typo. ([#745](https://github.com/googleapis/google-api-python-client/pull/745))
  - Remove compatibility badges. ([#746](https://github.com/googleapis/google-api-python-client/pull/746))
  - Fix TypeError: search_analytics_api_sample.py #732 ([#742](https://github.com/googleapis/google-api-python-client/pull/742))
  - Correct response access ([#750](https://github.com/googleapis/google-api-python-client/pull/750))
  - Fix link to API explorer ([#760](https://github.com/googleapis/google-api-python-client/pull/760))
  - Fix argument typo in oauth2 code example ([#763](https://github.com/googleapis/google-api-python-client/pull/763))
  - Recommend install with virtualenv ([#768](https://github.com/googleapis/google-api-python-client/pull/768))
  - Fix capitalization in docs/README.md ([#770](https://github.com/googleapis/google-api-python-client/pull/770))

  - Remove compatibility badges ([#796](https://github.com/googleapis/google-api-python-client/pull/796))
  - Remove mentions of pycrypto ([#799](https://github.com/googleapis/google-api-python-client/pull/799))
  - Fix typo in model.py
  - Add note about Google Ads llibrary ([#814](https://github.com/googleapis/google-api-python-client/pull/814))

  
  Internal / Testing Changes
  - Blacken ([#772](https://github.com/googleapis/google-api-python-client/pull/722))
  - Move kokoro configs ([#832](https://github.com/googleapis/google-api-python-client/pull/832))
  
### v1.7.11
  Version 1.7.11

  Bugfix release

  Implementation Changes
  - Pass library and Python version in x-goog-api-client header ([#734](https://github.com/googleapis/google-api-python-client/pull/734))

  Documentation
  - Fix typo in filename used in 'docs/auth.md' ([#736](https://github.com/googleapis/google-api-python-client/pull/736))

  
### v1.7.10
  Version 1.7.10

  Bugfix release

  Implementation Changes
  - Decode service to utf-8 ([#723](https://github.com/googleapis/google-api-python-client/pull/723))
  - Use print() function in both Python2 and Python 3 ([#722](https://github.com/googleapis/google-api-python-client/pull/722))
  - Make http.MediaFileUpload close its file descriptor ([#600](https://github.com/googleapis/google-api-python-client/pull/600))
  - Never make 'body' required ([#718](https://github.com/googleapis/google-api-python-client/pull/718))

  Documentation
  - Add compatability check badges to README ([#691](https://github.com/googleapis/google-api-python-client/pull/691))
  - Regenerate docs ([#696](https://github.com/googleapis/google-api-python-client/pull/696), [#700](https://github.com/googleapis/google-api-python-client/pull/700))
  - Create index file for dynamically generated docs ([#702](https://github.com/googleapis/google-api-python-client/pull/702))
  - Add docs folder with guides from developers.google.com ([#706](https://github.com/googleapis/google-api-python-client/pull/706), [#710](https://github.com/googleapis/google-api-python-client/pull/710))

  Internal / Testing Changes
  - Fix http.py, lint errors, unit test ([#724](https://github.com/googleapis/google-api-python-client/pull/724))
  - tox.ini: Look for Python syntax errors and undefined names ([#721](https://github.com/googleapis/google-api-python-client/pull/721))


### v1.7.9
  Version 1.7.9

  Bugfix release
  - Remove Django Samples. ([#657](https://github.com/googleapis/google-api-python-client/pull/657))
  - Call request_orig with kwargs ([#658](https://github.com/googleapis/google-api-python-client/pull/658))

### v1.7.8
  Version 1.7.8

  Bugfix release
  - Convert '$' in method name to '_' ([#616](https://github.com/googleapis/google-api-python-client/pull/616))
  - Alias unitest2 import as unittest in test__auth.py ([#613](https://github.com/googleapis/google-api-python-client/pull/613))

### v1.7.7
  Version 1.7.7

    Bugfix release
    - Change xrange to range ([#601](https://github.com/google/google-api-python-client/pull/601))
    - Typo in http.py exception message. ([#602](https://github.com/google/google-api-python-client/pull/602))

    - Announce deprecation of Python 2.7 ([#603](https://github.com/google/google-api-python-client/pull/603))
    - Updates documentation for stopping channel subscriptions ([#598](https://github.com/google/google-api-python-client/pull/598))
    - Adding example for searchAppearance ([#414](https://github.com/google/google-api-python-client/pull/414))

    - Add badges ([#455](https://github.com/google/google-api-python-client/pull/455))

### v1.7.6
  Version 1.7.6

  Bugfix release

  - Add client-side limit for batch requests (#585)

### v1.7.5
  Version 1.7.5

  Bugfix release

  - Fix the client to respect the passed in developerKey and credentials

### v1.7.4
  Version 1.7.4

  Bugfix release

  - Catch ServerNotFoundError to retry the request (#532)

### v1.7.3
  Version 1.7.3

  Bugfix release

  - Make apiclient.sample_tools gracefully fail to import (#525).


### v1.7.2
  Version 1.7.2

  Bugfix release

  - Remove unnecessary check in apiclient/__ini__.py (#522).

### v1.7.1
  Version 1.7.1

  Bugfix release

  - Remove unnecessary check in setup.py (#518).

### v1.7.0
  Version 1.7.0

  This release drops the hard requirement on oauth2client and installs
  google-auth by default instead. oauth2client is still supported but will
  need to be explicitly installed.

  - Drop oauth2client dependency (#499)
  - Include tests in source distribution (#514)

### v1.6.7
  Version 1.6.7

  Bugfix release

  **Note**: The next release of this library will no longer directly depend on
    oauth2client. If you need to use oauth2client, you'll need to explicitly
    install it.

  - Make body optional for requests with no parameters. (#446)
  - Fix retying on socket.timeout. (#495)
  - Match travis matrix with tox testenv. (#498)
  - Remove oauth2client._helpers dependency. (#493)
  - Remove unused keyring test dependency. (#496)
  - discovery.py: remove unused oauth2client import. (#492)
  - Update README to reference GCP API client libraries. (#490)

### v1.6.6
  Version 1.6.6

  Bugfix release

  - Warn when constructing BatchHttpRequest using the legacy batch URI (#488)
  - Increase the default media chunksize to 100MB. (#482)
  - Remove unnecessary parsing of mime headers in HttpRequest.__init__ (#467)

### v1.6.5
  Version 1.6.5

  Bugfix release

  - Proactively refresh credentials when applying and treat a missing
    `access_token` as invalid. Note: This change reveals surprising behavior
    between default credentials and batches. If you allow
    `googleapiclient.discovery.build` to use default credentials *and* specify
    different credentials by providing `batch.execut()` with an explicit `http`
    argument, your individual requests will use the default credentials and
    *not* the credentials specified to the batch http. To avoid this, tell
    `build` explicitly not to use default credentials by specifying
    `build(..., http=httplib2.Http()`. (#469)
  - Remove mutual exclusivity check for developerKey and credentials (#465)
  - Handle unknown media length. (#406)
  - Handle variant error format gracefully. (#459)
  - Avoid testing against Django >= 2.0.0 on Python 2. (#460)

### v1.6.4
  Version 1.6.4

  Bugfix release

  - Warn when google-auth credentials are used but google-auth-httplib2 isn't available. (#443)

### v1.6.3
  Version 1.6.3

  Bugfix release

  - Add notification of maintenance mode to README. (#410)
  - Fix generation of methods with abnormal page token conventions. (#338)
  - Raise ValueError is credentials and developerKey are both specified. (#358)
  - Re-generate documentation. (#364, #373, #401)
  - Fix method signature documentation for multiline required parameters. (#374)
  - Fix ZeroDivisionError in MediaDownloadProgress.progress. (#377)
  - Fix dead link to WebTest in README. (#378)
  - Fix details missing in googleapiclient.errors.HttpError. (#412)
  - Don't treat httplib2.Credentials as oauth credentials. (#425)
  - Various fixes to the Django sample. (#413)

### v1.6.2
  Version 1.6.2

  Bugfix release

  - Fixed a bug where application default credentials would still be used even
    when a developerKey was specified. (#347)
  - Official support for Python 3.5 and 3.6. (#341)
 
### v1.6.1
  Version 1.6.1

  Bugfix release

  - Fixed a bug where using google-auth with scoped credentials would fail. (#328)

### v1.6.0
  Version 1.6.0

  Release to drop support for Python 2.6 and add support for google-auth.

  - Support for Python 2.6 has been dropped. (#319)
  - The credentials argument to discovery.build and discovery.build_from_document
    can be either oauth2client credentials or google-auth credentials. (#319)
  - discovery.build and discovery.build_from_document now unambiguously use the
    http argument to make all requests, including the request for the discovery
    document. (#319)
  - The http and credentials arguments to discovery.build and
    discovery.build_from_document are now mutually exclusive, eliminating a
    buggy edge case. (#319)
  - If neither http or credentials is specified to discovery.build and
    discovery.build_from_document, then Application Default Credentials will
    be used. The library prefers google-auth for this if it is available, but
    can also use oauth2client's implementation. (#319)
  - Fixed resumable upload failure when receiving a 308 response. (#312)
  - Clarified the support versions of Python 3. (#316)

### v1.5.5
  Version 1.5.5

  Bugfix release

  - Allow explicit MIME type specification with media_mime_type keyword argument.
  - Fix unprintable representation of BatchError with default constructor. (#165)
  - Refresh all discovery docs, not just the preferred ones. (#298)
  - Update minimum httplib2 dependency to >=0.9.2.

### v1.5.4
  Version 1.5.4

  Bugfix release

  - Properly handle errors when the API returns a mapping or sequence. (#289)
  - Upgrade to unified uritemplate 3.0.0. (#293)
  - Allow oauth2client 4.0.0, with the caveat that file-based discovery
    caching is disabled.

### v1.5.3
  Version 1.5.3

  Bugfix release

  - Fixed import error with oauth2client >= 3.0.0. (#270)

### v1.5.2
  Version 1.5.2

  Bugfix release

  - Allow using oauth2client >= 1.5.0, < 4.0.0. (#265)
  - Fix project_id argument description. (#257)
  - Retry chunk uploaded on rate limit exceeded errors. (#255)
  - Obtain access token if necessary in BatchHttpRequest.execute(). (#232)
  - Warn when running tests using HttpMock without having a cache. (#261)

### v1.5.1
  Version 1.5.1

  Bugfix release

  - Allow using versions of oauth2client < 2.0.0. (#197)
  - Check both current and new API discovery URL. (#202)
  - Retry http requests on connection errors and timeouts. (#218)
  - Retry http requests on rate limit responses. (#201)
  - Import guards for ssl (for Google App Engine). (#220)
  - Use named loggers instead of the root logger. (#206)
  - New search console example. (#212)

### v1.5.0
  Version 1.5.0

  Release to support oauth2client >= 2.0.0.

  - Fix file stream recognition in Python 3 (#141)
  - Fix non-resumable binary uploads in Python 3 (#147)
  - Default to 'octet-stream' if mimetype detection fails (#157)
  - Handle SSL errors with retries (#160)
  - Fix incompatibility with oauth2client v2.0.0 (#182)

### v1.4.2
  Version 1.4.2

  Add automatic caching for the discovery docs.

### v1.4.1
  Version 1.4.1

  Add the googleapiclient.discovery.Resource.new_batch_http_request method.

### v1.4.0
  Version 1.4.0

  Python 3 support.

### v1.3.2
  Version 1.3.2

  Small bugfix release.

  - Fix an infinite loop for downloading small files.
  - Fix a unicode error in error encoding.
  - Better handling of `content-length` in media requests.
  - Add support for methodPath entries containing colon.

### v1.3.1
  Version 1.3.1

  Quick release for a fix around aliasing in v1.3.

### v1.3
  Version 1.3

  Add support for the Google Application Default Credentials.
  Require python 2.6 as a minimum version.
  Update several API samples.
  Finish splitting out oauth2client repo and update tests.
  Various doc cleanup and bugfixes.

  Two important notes:
    * We've added `googleapiclient` as the primary suggested import
      name, and kept `apiclient` as an alias, in order to have a more
      appropriate import name. At some point, we will remove `apiclient`
      as an alias.
    * Due to an issue around in-place upgrades for Python packages,
      it's not possible to do an upgrade from version 1.2 to 1.3. Instead,
      setup.py attempts to detect this and prevents it. Simply remove
      the previous version and reinstall to fix this.

### v1.2
  Version 1.2

  The use of the gflags library is now deprecated, and is no longer a
    dependency. If you are still using the oauth2client.tools.run() function
    then include gflags as a dependency of your application or switch to
    oauth2client.tools.run_flow.
  Samples have been updated to use the new apiclient.sample_tools, and no
    longer use gflags.
  Added support for the experimental Object Change Notification, as found in
    the Cloud Storage API.
  The oauth2client App Engine decorators are now threadsafe.

  - Use the following redirects feature of httplib2 where it returns the
    ultimate URL after a series of redirects to avoid multiple hops for every
    resumable media upload request.
  - Updated AdSense Management API samples to V1.3
  - Add option to automatically retry requests.
  - Ability to list registered keys in multistore_file.
  - User-agent must contain (gzip).
  - The 'method' parameter for httplib2 is not positional. This would cause
    spurious warnings in the logging.
  - Making OAuth2Decorator more extensible. Fixes Issue 256.
  - Update AdExchange Buyer API examples to version v1.2.


### v1.1
  Version 1.1

  Add PEM support to SignedJWTAssertionCredentials (used to only support
  PKCS12 formatted keys). Note that if you use PEM formatted keys you can use
  PyCrypto 2.6 or later instead of OpenSSL.

  Allow deserialized discovery docs to be passed to build_from_document().

  - Make ResumableUploadError derive from HttpError.
  - Many changes to move all the closures in apiclient.discovery into real
  -  classes and objects.
  - Make from_json behavior inheritable.
  - Expose the full token response in OAuth2Client and OAuth2Decorator.
  - Handle reasons that are None.
  - Added support for NDB based storing of oauth2client objects.
  - Update grant_type for AssertionCredentials.
  - Adding a .revoke() to Credentials. Closes issue 98.
  - Modify oauth2client.multistore_file to store and retrieve credentials
    using an arbitrary key.
  - Don't accept 403 challenges by default for auth challenges.
  - Set httplib2.RETRIES to 1.
  - Consolidate handling of scopes.
  - Upgrade to httplib2 version 0.8.
  - Allow setting the response_type in OAuth2WebServerFlow.
  - Ensure that dataWrapper feature is checked before using the 'data' value.
  - HMAC verification does not use a constant time algorithm.

### v1.0
 Version 1.0

  - Changes to the code for running tests and building releases.

### v1.0c3
 Version 1.0 Release Candidate 3

  - In samples and oauth2 decorator, escape untrusted content before displaying it.
  - Do not allow credentials files to be symlinks.
  - Add XSRF protection to oauth2decorator callback 'state'.
  - Handle uploading chunked media by stream.
  - Handle passing streams directly to httplib2.
  - Add support for Google Compute Engine service accounts.
  - Flows no longer need to be saved between uses.
  - Change GET to POST if URI is too long. Fixes issue #96.
  - Add a keyring based Storage.
  - More robust picking up JSON error responses.
  - Make batch errors align with normal errors.
  - Add a Google Compute sample.
  - Token refresh to work with 'old' GData API
  - Loading of client_secrets JSON file backed by a cache.
  - Switch to new discovery path parameters.
  - Add support for additionalProperties when printing schema'd objects.
  - Fix media upload parameter names. Reviewed in http://codereview.appspot.com/6374062/
  - oauth2client support for URL-encoded format of exchange token response (e.g.  Facebook)
  - Build cleaner and easier to read docs for dynamic surfaces.

### v1.0c2
 Version 1.0 Release Candidate 2

  - Parameter values of None should be treated as missing. Fixes issue #144.
  - Distribute the samples separately from the library source. Fixes issue #155.
  - Move all remaining samples over to client_secrets.json. Fixes issue #156.
  - Make locked_file.py understand win32file primitives for better awesomeness.

### v1.0c1
 Version 1.0 Release Candidate 1

 - Documentation for the library has switched to epydoc:
     http://google-api-python-client.googlecode.com/hg/docs/epy/index.html
 - Many improvements for media support:
   * Added media download support, including resumable downloads.
   * Better handling of streams that report their size as 0.
   * Update Media Upload to include io.Base and also fix some bugs.
 - OAuth bug fixes and improvements.
   * Remove OAuth 1.0 support.
   * Added credentials_from_code and credentials_from_clientsecrets_and_code.
   * Make oauth2client support Windows-friendly locking.
   * Fix bug in StorageByKeyName.
   * Fix None handling in Django fields. Reviewed in http://codereview.appspot.com/6298084/. Fixes issue #128.
 - Add epydoc generated docs. Reviewed in http://codereview.appspot.com/6305043/
 - Move to PEP386 compliant version numbers.
 - New and updated samples
   * Ad Exchange Buyer API v1 code samples.
   * Automatically generate Samples wiki page from README files.
   * Update Google Prediction samples.
   * Add a Tasks sample that demonstrates Service accounts.
   * new analytics api samples. Reviewed here: http://codereview.appspot.com/5494058/
 - Convert all inline samples to the Farm API for consistency.

### v1.0beta8
 - Updated meda upload support.
 - Many fixes for batch requests.
 - Better handling for requests that don't require a body.
 - Fix issues with Google App Engine Python 2.7 runtime.
 - Better support for proxies.
 - All Storages now have a .delete() method.
 - Important changes which might break your code:
    * apiclient.anyjson has moved to oauth2client.anyjson.
    * Some calls, for example, taskqueue().lease() used to require a parameter
      named body. In this new release only methods that really need to send a body
      require a body parameter, and so you may get errors about an unknown
      'body' parameter in your call. The solution is to remove the unneeded
      body={} parameter.

### v1.0beta7
 - Support for batch requests.  http://code.google.com/p/google-api-python-client/wiki/Batch
 - Support for media upload.  http://code.google.com/p/google-api-python-client/wiki/MediaUpload
 - Better handling for APIs that return something other than JSON.
 - Major cleanup and consolidation of the samples.
 - Bug fixes and other enhancements:
   72  Defect  Appengine OAuth2Decorator: Convert redirect address to string
   22  Defect  Better error handling for unknown service name or version
   48  Defect  StorageByKeyName().get() has side effects
   50  Defect  Need sample client code for Admin Audit API
   28  Defect  better comments for app engine sample   Nov 9
   63  Enhancement Let OAuth2Decorator take a list of scope
