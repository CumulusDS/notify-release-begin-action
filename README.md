[![Create Release][release-badge]][release-url]
[![Import Labels][import-labels-badge]][import-labels-url]
[![Sync Labels][sync-labels-badge]][sync-labels-url]
[![PR AutoLabeler][autolabeler-badge]][autolabeler-url]
[![Assigner][assigner-badge]][assigner-url]

Notify slack channels when a production release has begun

### Inputs
#### `SLACK_WEBHOOK`

#### ``


#### ``



### Example usage
```yaml
      - name: action
        uses: CumulusDS/notify-release-begin-action@v1
        with:
          SLACK_WEBHOOK: ${{ secrets.SLACK_WEBHOOK }}
```

[release-badge]: https://github.com/CumulusDS/notify-release-begin-action/actions/workflows/release.yml/badge.svg
[release-url]: https://github.com/CumulusDS/notify-release-begin-action/actions/workflows/release.yml
[import-labels-badge]: https://github.com/CumulusDS/notify-release-begin-action/actions/workflows/labels_import.yml/badge.svg
[import-labels-url]: https://github.com/CumulusDS/notify-release-begin-action/actions/workflows/labels_import.yml
[sync-labels-badge]: https://github.com/CumulusDS/notify-release-begin-action/actions/workflows/labels_sync.yml/badge.svg
[sync-labels-url]: https://github.com/CumulusDS/notify-release-begin-action/actions/workflows/labels_sync.yml
[autolabeler-badge]: https://github.com/CumulusDS/notify-release-begin-action/actions/workflows/autolabeler.yml/badge.svg
[autolabeler-url]: https://github.com/CumulusDS/notify-release-begin-action/actions/workflows/autolabeler.yml
[assigner-badge]: https://github.com/CumulusDS/notify-release-begin-action/actions/workflows/assign.yml/badge.svg
[assigner-url]: https://github.com/CumulusDS/notify-release-begin-action/actions/workflows/assign.yml
