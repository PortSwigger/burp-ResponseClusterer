# ResponseClusterer

This extension clusters similar responses together, and shows a summary with one request/response per cluster. This allows the tester to get an overview of the tested website's responses from all Burp Suite tools. This is powerful, because it adds an additional vulnerability detection mechanism. Instead of using known techniques (error-based, inband sleep-based, out-of-band Burp Collaborator, etc.), this extension will assist in finding anomalies with a semi-automated approach allowing you to review a selection of server responses.

Options for determining similarity can be configured, in case too few or too many clusters are generated. Because the similarity comparison can consume a lot of ressources, only small, in-scope responses that have interesting response codes, file extensions and MIME types are processed.

The extension persists results in the project.