# Changelog  
  
| modName    | 6S Service Compartment Tubes (SCT)                                |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-SA-4.0                                                      |
| author     | Nothke and zer0Kerbal                                             |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209841-*/) |
| github     | (https://github.com/zer0Kerbal/ServiceCompartmentTubes)           |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/ServiceTubes)         |
| spacedock  | (https://spacedock.info/mod/3123)                                 |
| ckan       | Service-Compartments-6S                                           |

## Version 1.3.99.0-adoption - `<Thank you Nothke>`

* Released
  * 07 Nov 2022
  * for Kerbal Space Program 1.12.4
  * by zer0Kerbal

### Summary 1.3.99.0

* four (4) new parts
  * 1.25m Tall
  * 2.5m Tall
  * 3.75m
  * 3.75m Tall
* complete stock update
* still supports Firespitter

### Adoption by zer0Kerbal

* Update License
  * Updated License: CC BY-SA 4.0
    * was: CC BY-NC-SA 4.0
* closes #37 - Update License

### Create <ServiceCompartmentTubes.cfg>

* Add localized tags to parts
* Create
  * <ServiceCompartmentTubes.cfg> v1.0.0.0
    * adds localized tags to parts
* closes #36 - Create <ServiceCompartmentTubes.cfg>

### Documentation 1.3.99.0

* create / update readme.md
* <ServiceCompartmentTubes.version>
  * update
  * remove [KSP_VERSION_MAX] section

### Create GitHub Pages

* Create GitHub Pages
  * docs/
    * [`_config.yml`]
    * [Attribution.md] v1.0.7.1
    * [ManualInstallation.md] v1.1.8.0
    * [404.md] v1.0.3.2
    * [LegalMumboJumbo.md] v1.0.5.1
    * [Localizations.md] v1.1.7.0
    * [Marketing.md] v1.0.1.0
    * [Notices.md] v1.0.1.0
    * [PartsCatalog.md] v1.1.4.1
    * [Why.md] v1.1.0.0
* closes #32 - Create GitHub Pages

### Part Asset Updates

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
  * textures to png/dds
    * <6scomp 4.mbm> 1.025mb --> <6scomp_n 7.png> 100kb
    * <6scomp_n 7.mbm> 1.025mb --> <6scomp 4.png> 134kb
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* closes #35 - Part Asset Updates

### Create HeroLogo.png

* Create
  * HeroLogo.png
  * copy/convert to HeroLogo.jpg
* closes #33 - Create HeroLogo.png

### Compatibility 1.3.99.0

* [Firespitter.cfg] v1.0.0.0
  * FSanimateGeneric

### Parts 1.3.99.0

* New Parts (collaborative forum effort)
  * <sct-sercom-1mT.cfg> v1.0.0.0
  * <sct-sercom-2mT.cfg> v1.0.0.0
  * <sct-sercom-3m.cfg> v1.0.0.0
  * <sct-sercom-3mT.cfg> v1.0.0.0
* Rename
  * File names
    * <SerCom1m.cfg> --> <sct-sercom-1m.cfg>
    * <SerCom1mT.cfg> --> <sct-sercom-1mT.cfg>
    * <SerCom2m.cfg> --> <sct-sercom-2m.cfg>
    * <SerCom2mT.cfg> --> <sct-sercom-2mT.cfg>
    * <SerCom3m.cfg> --> <sct-sercom-3m.cfg>
    * <SerCom3mT.cfg> --> <sct-sercom-3mT.cfg>
  * Part names
    * SerCom1m --> sct-sercom-1m
    * SerCom1mT --> sct-sercom-1mT
    * SerCom2m --> sct-sercom-2m
    * SerCom2mT --> sct-sercom-2mT
    * SerCom3m --> sct-sercom-3m
    * SerCom3mT --> sct-sercom-3mT
  * Create
    * [ghostparts.cfg]
    * this patch which will go away
  * closes #38 - ghostparts
* Replace [FSanimateGeneric] with [ModuleAnimateGeneric]
* Lint
* Update category
* Add stuff

### Localization

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
  * closes #34 - Create Localization directory and contents
* Localize
  * Parts
  * closes #28 - Part Localization
  * Modules
    * [ModuleAnimateGeneric]
    * [FSanimateGeneric]
* closes #11 - English <us-en.cfg>
* closes #10 - Localization - Master
* closes #39 - Localization

### Create Thumbs

* Create
  * @thumbs/
  * add thumbnails
* closes #40 - Create Thumbs

### Create Agency

* Create
  * Agency/Agents.cfg
  * create _scaled.truecolor (64x40)
  * create flag (512x320)
* closes #41 - Create Agency

### Status 1.3.99.0

* Issues
  * closes #1 - Service Compartment Tubes (SCT) 1.3.99.0-adoption `<Thank you nothke>` edition
  * closes #2 - 1.3.99.0 Verify Legal Mumbo Jumbo
  * closes #3 - 1.3.99.0 Create Documentation
  * closes #4 - 1.3.99.0 Create Social Media

---                                             |

## Version 1.3.0.0-release - `<Archival>`

* 04 Dec 2014
* Released for Kerbal Space Program 0.25
* Last release by original author

### Changes 1.3.0.0

* Fixed part scaling issues introduced with 0.25.
  * Special thanks to [NoMrBond](http://forum.kerbalspaceprogram.com/members/71066-NoMrBond)
* Fixed prices for career. 1m and 2m tubes now cost 150 and 200, respectively
* Bundled a fresh Firespitter .dll

### Status 1.3.0.0

* Issues
  * closes #8 - 1.3.0.0-release
  * closes #5 - Previous Archive Release

---

## Version 1.2.0.0-release - `<Archival>`

* 09 May 2014
* Released for Kerbal Space Program 0.23.5

### Changes 1.2.0.0

* Added latest Firespitter plugin compatible with 0.23.5

### Status 1.2.0.0

* Issues
  * closes #7 - 1.2.0.0-release
  * updates #5 - Previous Archive Release

---

## Version 1.1.0.0-release - `<Archival>`

* 09 May 2013
* Released for Kerbal Space Program 0.23.5

### Changes 1.1.0.0

* added new Firespitter version
* FAR now shields everything inside
* bay opening action group is now not functional (although it appears in menu)

### Status 1.1.0.0

* Issues
  * closes #6 - 1.1.0.0-release
  * updates #5 - Previous Archive Release

---
