# Ryanhallactions
Github Actions made by Ryan Hall, <ryan.hall@wiz.io>

# Contents

* [.github/workflows/wizcli-scan-dockerfile.yml](wizcli-scan-dockerfile.yml) - Will use the `wizcli` to scan a Dockerfile in this repository root. It will produce results to the Workflow's summary page, indicating a PASS :white_check_mark: or FAIL :x: , with a link to the scan results.
  * DEPENDENCIES:
    * `secrets.CLIENT_ID` - Wiz Service Account Client ID
    * `secrets.CLIENT_SECRET` - Wiz Service Account Client Secret
