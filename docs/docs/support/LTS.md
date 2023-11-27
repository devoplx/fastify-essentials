---
id: lts
title: Long Term Support
---


Fastify Essentials Long Term Support (LTS) is provided according to the schedule laid out
in this document:

1. **Major** releases, "X" release of [semantic versioning][semver] X.Y.Z release
  versions, are supported untill the next major release version and or a secruity 
	updates or when [Fastify](https://github.com/fastify/fastify) releases a new major 
	version. The release date of any specific Fastify Essentials version can be found at
  [Fastify Essentials Releases](https://github.com/devoplx/fastify-essentials/releases). 
	The release date of any specific Fastify version can be found at
  [Fastify Releases](https://github.com/fastify/fastify/release).
	All Major releases are tested, and performs well with the current fastify version.

	:::note
	We may maintain the previous major release, if the current major version did not provide any 
	breaking changes to any of the existing api's.
	> this is not guaranteed, so it is recommended to always update the latest version.
	:::

2. **Minor** releases, "Y" release of [semantic versioning][semver] X.Y.Z release
	versions, are only supported untill the next major release or minor version or secruity updates.
	The release date of any specific Fastify Essentials version can be found at
	[Fastify Essentials Releases](https://github.com/devoplx/fastify-essentials/releases). 

	:::danger
	Any previous minor release would not be supported or maintained, including any secruity updates. 
	:::

3. **Patch** releases, "Z" release of [semantic versioning][semver] X.Y.Z release
	versions, are only supported untill the next patch, minor, or major release.
	The release date of any specific Fastify Essentials version can be found at
	[Fastify Essentials Releases](https://github.com/devoplx/fastify-essentials/releases). 

	:::info
	patchs, do not include new changes or secruity updates, so it is safe to not upgrade right away. 
	:::

A "month" is defined as 30 consecutive days.

> ## Security Releases and Semver
>
> As a consequence of providing  support for major releases, there are
> occasions where we need to release breaking changes as a _minor_ version
> release. Such changes will _always_ be noted in the [release
> notes](https://github.com/devoplx/fastify-essentials/releases).
>
> We do not provide support to avoid theses changes due to the fact of a public 
> secruity issue. We always provide support at our issue [page](https://github.com/devoplx/fastify-essentials/issues) and will provide a guide to fix the changes.

[semver]: https://semver.org/

### Schedule
<a id="lts-schedule"></a>

| Version | Release Date | Deprecated | 
| :------ | :----------- | :----------| 
| 0.x.x   | 2023-11-27   | [❌]       | 
