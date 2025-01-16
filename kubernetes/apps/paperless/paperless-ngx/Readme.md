


Paramters
```
--api-bind-ip string Set the IP address the API should bind to for incoming connections
--api-body-limit string Set the body limit for multipart/form-data requests - it accepts values like 5MB, 1GB, etc
--api-disable-download-from Disable the download from feature
--api-disable-health-check-logging Disable health check logging
--api-download-from-allow-list string Set the allowed URLs for the download from feature using a regular expression
--api-download-from-deny-list string Set the denied URLs for the download from feature using a regular expression
--api-download-from-max-retry int Set the maximum number of retries for the download from feature (default 4)
--api-enable-basic-auth Enable basic authentication - will look for the GOTENBERG_API_BASIC_AUTH_USERNAME and GOTENBERG_API_BASIC_AUTH_PASSWORD environment variables
--api-port int Set the port on which the API should listen (default 3000)
--api-port-from-env string Set the environment variable with the port on which the API should listen - override the default port
--api-root-path string Set the root path of the API - for service discovery via URL paths (default "/")
--api-start-timeout duration Set the time limit for the API to start (default 30s)
--api-timeout duration Set the time limit for requests (default 30s)
--api-tls-cert-file string Path to the TLS/SSL certificate file - for HTTPS support
--api-tls-key-file string Path to the TLS/SSL key file - for HTTPS support
--api-trace-header string Set the header name to use for identifying requests (default "Gotenberg-Trace")
--chromium-allow-file-access-from-files Allow file:// URIs to read other file:// URIs
--chromium-allow-insecure-localhost Ignore TLS/SSL errors on localhost
--chromium-allow-list string Set the allowed URLs for Chromium using a regular expression
--chromium-auto-start Automatically launch Chromium upon initialization if set to true; otherwise, Chromium will start at the time of the first conversion
--chromium-clear-cache Clear Chromium cache between each conversion
--chromium-clear-cookies Clear Chromium cookies between each conversion
--chromium-deny-list string Set the denied URLs for Chromium using a regular expression (default "^file:(?!//\\/tmp/).*")
--chromium-disable-javascript Disable JavaScript
--chromium-disable-routes Disable the routes
--chromium-disable-web-security Don't enforce the same-origin policy
--chromium-host-resolver-rules string Set custom mappings to the host resolver
--chromium-ignore-certificate-errors Ignore the certificate errors
--chromium-incognito Start Chromium with incognito mode
--chromium-max-queue-size int Maximum request queue size for Chromium. Set to 0 to disable this feature
--chromium-proxy-server string Set the outbound proxy server; this switch only affects HTTP and HTTPS requests
--chromium-restart-after int Number of conversions after which Chromium will automatically restart. Set to 0 to disable this feature
--chromium-start-timeout duration Maximum duration to wait for Chromium to start or restart (default 20s)
--gotenberg-graceful-shutdown-duration duration Set the graceful shutdown duration (default 30s)
--libreoffice-auto-start Automatically launch LibreOffice upon initialization if set to true; otherwise, LibreOffice will start at the time of the first conversion
--libreoffice-disable-routes Disable the routes
--libreoffice-max-queue-size int Maximum request queue size for LibreOffice. Set to 0 to disable this feature
--libreoffice-restart-after int Number of conversions after which LibreOffice will automatically restart. Set to 0 to disable this feature (default 10)
--libreoffice-start-timeout duration Maximum duration to wait for LibreOffice to start or restart (default 20s)
--log-fields-prefix string Prepend a specified prefix to each field in the logs
--log-format string Specify the format of logging. Options include auto, json, or text (default "auto")
--log-level string Choose the level of logging detail. Options include error, warn, info, or debug (default "info")
--pdfengines-convert-engines strings Set the PDF engines and their order for the convert feature - empty means all (default [libreoffice-pdfengine])
--pdfengines-disable-routes Disable the routes
--pdfengines-merge-engines strings Set the PDF engines and their order for the merge feature - empty means all (default [qpdf,pdfcpu,pdftk])
--pdfengines-read-metadata-engines strings Set the PDF engines and their order for the read metadata feature - empty means all (default [exiftool])
--pdfengines-split-engines strings Set the PDF engines and their order for the split feature - empty means all (default [pdfcpu,qpdf,pdftk])
--pdfengines-write-metadata-engines strings Set the PDF engines and their order for the write metadata feature - empty means all (default [exiftool])
--prometheus-collect-interval duration Set the interval for collecting modules' metrics (default 1s)
--prometheus-disable-collect Disable the collect of metrics
--prometheus-disable-route-logging Disable the route logging
```