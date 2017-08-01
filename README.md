# BOSH Release for [Hadoop](http://hadoop.apache.org)

## Current Status

## Usage

To use this bosh release, first upload it to your bosh:

```
ENV=<my BOSH environment alias>
git clone github.com/spiegela/hadoop-bosh-release.git
cd hadoop-bosh-release
bosh -e $ENV upload-release
bosh -e $ENV deploy ./manifests/hadoop.yml
```

### TODO (also reflected in [issues](https://github.com/spiegela/hadoop-bosh-release/issues))

### Development

As a developer of this release, create new releases and upload them:

```
ENV=<my BOSH environment alias>
bosh create-release --force && bosh -e $ENV upload-release
```
