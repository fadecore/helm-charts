# Helm Charts

This functionality is in beta and is subject to change. The code is provided as-is with no warranties. Beta features are not subject to the support SLA of official GA features.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repository as follows:

```console
helm repo add fadecore https://fadecore.github.io/helm-charts
```

You can then run `helm search repo fadecore` to see the charts.

If you want to pull the helm charts from an oci registry you can check availability with `helm show chart oci://ghcr.io/fadecore/helm-charts/$CHART_NAME`

## Contributing

The source code of all charts can be found on Github: <https://github.com/fadecore/helm-charts/>

<!-- Keep full URL links to repo files because this README syncs from main to gh-pages.  -->
We'd love to have you contribute!

## License

<!-- Keep full URL links to repo files because this README syncs from main to gh-pages.  -->
[MIT License](https://github.com/fadecore/helm-charts/blob/main/LICENSE).

## Helm charts build status

![Release Charts](https://github.com/fadecore/helm-charts/workflows/Release%20Charts/badge.svg?branch=main)
