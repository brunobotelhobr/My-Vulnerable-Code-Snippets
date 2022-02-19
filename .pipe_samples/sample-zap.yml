name: owasp-zap-api-scan
on: push

jobs:
  zap_scan:
    name: Scan REST APIs
    runs-on: ubuntu-latest
    steps:
      - name: ZAP Scan for crudall API
        uses: zaproxy/action-api-scan@v0.1.0
        with:
          format: openapi
          target: 'https://zapsample.demo.community.intersystems.com/crudall/_spec'

