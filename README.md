# The Darkvault OSGI bundle repository.
This repository contains dependencies and releases for the darkvault projects.

## Adding a new artifact
You can add a new artifact if you've write access. The easiest way to do this is to
use bnd.

      $ bnd put --repo . put https://exmple.com/bundles/mybundle.jar ...

See 'bnd help repo put' for more information. 
 
## Rebuilding the index (index.xml.gz) when adding bundles
After you've added a number of bundles you must update the index.

     $ ./gradlew
