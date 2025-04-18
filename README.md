# trivy-plugin-webhook

## Installation
```shell
trivy plugin install github.com/aquasecurity/trivy-plugin-webhook
```

## Usage
```shell
trivy webhook -- <plugin flags> -- <trivy args>
```

## Command Line Flags

| Flag       | Description | Required | Example                       |
|------------|-------------|----------|-------------------------------|
| --url      | Webhook URL | Yes      | `--url="example.com"`         |
| --hostname | Hostname    | No       | `--hostname="myhostname.com"` |
