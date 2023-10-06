[[README DE](https://github.com/kurwjan/LanisAPI/blob/master/README-DE.md)]  [[README EN](https://github.com/kurwjan/LanisAPI/blob/master/README.md)]

# LanisAPI

> # ⚠ Notice
> **Because the Schulportal Hessen changes quickly and is very fragmented, *(like the backwards compability with Linux libraries)* can some functions at specifc schools or after a time not be working anymore.**

## What is this?
It's an unofficial Python library for the Schulportal Hessen. Also available on [PyPi](https://pypi.org/project/lanisapi/).

## How do I install it?
```
$ pip install lanisapi
```
Required is Python 3.11. *(older versions should definitely work too but I didn't tested it.)*

## Example
This example gives the substitution plan.
```python
from lanisapi import LanisClient

def main():
    client = LanisClient("schoolid", "name.lastname", "password")
    client.authenticate()
    print(client.get_substitution_plan())
    client.logout()
    
if __name__ == "__main__":
    main()
```
More infos at the [wiki](https://github.com/kurwjan/LanisAPI/wiki/First-steps).

## Overview of future Features, Problems and other things [here](https://github.com/users/kurwjan/projects/2).

## How can I help?
1. You can report Problems at *Issues*.
2. You can suggest Ideas at *Issues*.
3. **Extra nice**: You can contribute to this project. If you're new to contributing, look [here](https://docs.github.com/en/get-started/quickstart/contributing-to-projects).

## Credits
The Javascript project [SPHclient](https://github.com/alessioC42/SPHclient) from [@alessioC42](https://github.com/alessioC42) helped me to understand the shitpile *Schulportal Hessen*.

The Android-App [sph-planner](https://github.com/koenidv/sph-planner) *(if you know Kotlin, you can contribute to this app)* from [@koenidv](https://github.com/koenidv) helped me to understand the Level 2 encryption.

Other projects that didn't helped me but are cool:

* Flutter Android app [SPH-Vertretungsplan](https://github.com/alessioC42/SPH-vertretungsplan) also from [@alessioC42](https://github.com/alessioC42)
* Javascript app [SchulportalApp](https://github.com/DerOwnerHD/SchulportalApp) from [DerOwnerHD](https://github.com/DerOwnerHD)
* Flutter Android app [lkwslr-sphplaner](https://github.com/flutter-preview/lkwslr-sphplaner) from [flutter-preview](https://github.com/flutter-preview)
* TypeScript library [Maria](https://github.com/elderguardian/maria) from [Elderguardian](https://github.com/elderguardian/)

## Notice
This project isn't officialy related to the Schulportal Hessen. It's only a unofficial libray, supported by the community.
