# Migrate supplementary files as submission files

The feature to create supplementary files was removed in OJS 3.x, therefore when upgrading from OJS 2.x to 3.x, the upgrade code will convert such files into public galleys.

If you don't agree or have concerns about it, and would rather have them to be turned into private, submission files, this patch is supposed to achieve this.

## Instructions

Before doing the migration from OJS 2.x to 3.2.x (as recommended in the documentation https://docs.pkp.sfu.ca/upgrading-ojs-2-to-3/en/upgrade-planning#decide-which-version-of-ojs-3-to-upgrade-to), apply the patch present on the file [supplementary-files.patch](supplementary-files.patch).
