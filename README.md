# ks-versions
A helper to release KubeSphere family repositories. Get more details from [ks-releaser](https://github.com/kubesphere-sigs/ks-releaser).

> Caution: currently, the resource files name must follow this pattern `{{.Name}}-{{.Version}}.yaml`.
> For instance, there is a project named `ks`, then you name the resource `ks-v0.0.1`. And the resource file name must be `ks-v0.0.1.yaml`.

## Wants to have a new release?

Please just create a Pull request to change `spec.phase` to `ready` of your desired project.
