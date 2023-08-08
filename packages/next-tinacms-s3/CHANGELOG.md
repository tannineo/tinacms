# next-tinacms-s3

## 1.3.2

### Patch Changes

- bc812441b: Use .mjs extension for ES modules

## 1.3.1

### Patch Changes

- 63dd98904: - Adds newly added images to the top of the list and selects them
  - Adds a refresh button to the image list
  - Fixes a bug where you could not upload images in a directory (Locally)
  - Adds a new folder button to the media manager
  - Logs error messages from the handlers so the user is aware of them (previously they were just swallowed and returned in the response message but this is harder to find)
- 400a7fdeb: Add the `mediaRoot` option to the s3 media store

## 1.3.0

### Minor Changes

- 817b10b8a: deliver multiple size thumbnails

## 1.2.0

### Minor Changes

- 4cd5cd4f7: Refactor: Remove previewSrc from imageAPI

### Patch Changes

- 0b7687424: support pdf uploads

## 1.1.1

### Patch Changes

- efd56e769: Remove license headers

## 1.1.0

### Minor Changes

- 48c4b3d48: Fix accept key in media stores

## 1.0.0

### Major Changes

- 958d10c82: Tina 1.0 Release

  Make sure you have updated to th "iframe" path: https://tina.io/blog/upgrading-to-iframe/

## 0.0.6

### Patch Changes

- 86dae3189: Fix dran'n'drop uploaded image not shown issue

## 0.0.5

### Patch Changes

- be40bfd71: Remove unnecessary media helper deps

## 0.0.4

### Patch Changes

- 2422e505d: Removed styled-components as a dependency in tinacms.
  Removed deprecated react-toolbar in @tinacms/toolkit.

## 0.0.3

### Patch Changes

- 112b7271d: fix vulnerabilities

## 0.0.2

### Patch Changes

- 3591c98e0: Introduce support for S3-backed media
