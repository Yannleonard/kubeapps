# The Kubeapps Components

### Kubeapps dashboard

The dashboard is the main UI component of the Kubeapps project. Written in Javascript, the dashboard uses the React Javascript library for the frontend.

Please refer to the [Kubeapps Dashboard Developer Guide](dashboard.md) for the developer setup.

### assetsvc

The `assetsvc` component is a micro-service that creates an API endpoint for accessing the metadata for charts in Helm chart repositories that's populated in a Postgresql server.

Please refer to the [Kubeapps assetsvc Developer Guide](assetsvc.md) for the developer setup.

### asset-syncer

The `asset-syncer` component is a tool that scans a Helm chart repository and populates chart metadata in the database. This metadata is then served by the `assetsvc` component.

Please refer to the [Kubeapps asset-syncer Developer Guide](asset-syncer.md) for the developer setup.
