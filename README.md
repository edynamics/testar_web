# testar_web

download chromedriver matching your chrome browser version
http://chromedriver.chromium.org/downloads
> unpack to c:/ (or change the path in the UI-tab "General Settings" OR bin/settings/webdriver_generic/test.settings SUTConnectorValue

# Usage
from UI > run bin/testar.bat
or
use npm scripts inside bin/settings/webdriver_generic/package.json

# Change website
in the UI-tab "General Settings" OR bin/settings/webdriver_generic/test.settings SUTConnectorValue
AND
change domainsAllowed in bin/settings/webdriver_generic/Protocol_webdriver_generic.java
