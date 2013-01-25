# Community BOSH release for CloudFoundry

## Release to your BOSH

To create and upload the latest final release to your BOSH:

```
git clone git://github.com/drnic/community-cf-release.git
cd community-cf-release
bosh upload release releases/1.yml
```

## Don't have a BOSH?

```
gem install bosh-bootstrap
bosh-bootstrap deploy --latest-stemcell
```

Choose AWS or OpenStack, select regions, choose some defaults, and choose the option to create a new "Inception VM" (if you don't know what it is, then you'll need one).

30 minutes or so later you will have a BOSH running. You can now run the commands above.

