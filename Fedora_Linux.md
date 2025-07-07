# Fedora_Linux

Fedora Linux is a Linux distribution developed by the Fedora Project. It was originally developed in 2003 as a continuation of the Red Hat Linux project. It contains software distributed under various free and open-source licenses and aims to be on the leading edge of open-source technologies. It is now the upstream source for CentOS Stream and Red Hat Enterprise Linux.
Since the release of Fedora 21 in December 2014, three editions have been made available: personal computer, server and cloud computing. This was expanded to five editions for containerization and Internet of Things (IoT) as of the release of Fedora 37 in November 2022. A new version of Fedora Linux is released every six months.
As of February 2016, Fedora Linux has an estimated 1.2 million users, and is also the distribution used by Linus Torvalds, creator of the Linux kernel (as of May 2020).


## Features

Fedora has a reputation for focusing on innovation, integrating new technologies early on and working closely with upstream Linux communities. Making changes upstream instead of specifically for Fedora Linux ensures that the changes are available to all Linux distributions.
Fedora Linux has a relatively short life cycle: Each version is usually supported for at least 13 months, where version X is supported only until 1 month after version X+2 is released and with approximately 6 months between most versions. Fedora users can upgrade from version to version without reinstalling.
The default desktop environment is GNOME, and the default user interface is the GNOME Shell. Other desktop environments are available, including KDE Plasma, COSMIC, Xfce, LXQt, LXDE, MATE, Cinnamon, and Budgie as well as window managers including i3, and Sway.
A live media drive can be created using Fedora Media Writer or the dd command, allowing users to try Fedora Linux without writing any changes to their hard drives.


### Package management
Most Fedora Linux editions use the RPM package management system and DNF as a tool to manage installed software. DNF uses libsolv, an external dependency resolver. Flatpak is also included by default.
The CoreOS and Silverblue editions are designed for operating system-level virtualization. These editions use rpm-ostree (a hybrid transactional image/package system), and traditional RPM (or other package management systems) can be used in containers.


### Security
Fedora Linux uses Security-Enhanced Linux by default, which implements a variety of security policies, including mandatory access controls, which Fedora adopted early on. Fedora provides a hardening wrapper, and does hardening for all of its packages by using compiler features such as position-independent executable (PIE). Fedora also ships with firewalld as a default firewall.


### Software
Fedora Workstation comes preinstalled with a wide range of software such as LibreOffice and Firefox. Additional software is available from the software repositories and can be installed using the DNF package manager or GNOME Software.
Additionally, extra repositories can be added to the system, so that software not available in Fedora Linux can be installed easily. Software that is not available via official Fedora repositories, either because it does not meet Fedora's definition of free software or because its distribution may violate US law, can be installed using third-party repositories. Popular third-party repositories include RPM Fusion free and non-free repositories. Fedora also provides users with an easy-to-use build system for creating their own repositories called Copr.
Since the release of Fedora 25, the operating system defaults to the Wayland display server protocol, which replaced the X Window System. As of Fedora 41, both the GNOME and KDE editions do not ship with X.Org Server session support by default.


### System installer

Fedora Linux uses Anaconda as the system installer.


## Editions

Beginning with Fedora 21, was available in three editions, expanded to six editions as of version 42.


### Workstation

The Fedora Workstation editions target users who want a reliable, user-friendly, and powerful operating system for their laptop or desktop computer while still being on the cutting edge of new technologies. They come with GNOME by default but other desktops can be installed, including KDE Plasma, which was promoted to a regular edition on the same level as Fedora Workstation with GNOME starting with Fedora 42.


=### Spins and remixes=

The Fedora project officially distributes different variations called "Fedora Spins" which are Fedora Linux with different desktop environments. The current official spins, as of Fedora 42, are Xfce, LXQt, MATE (with Compiz), Cinnamon, LXDE, SoaS, i3, Phosh (for use on PinePhone), Budgie, Sway, and COSMIC.
In addition to Spins, which are official variants of the Fedora system, the project allows unofficial variants to use the term "Fedora Remix" without asking for further permission, although a different logo (provided) is required.


### Atomic desktops

Fedora offers immutable editions known as "Atomic Desktops". Separate editions are offered per desktop environment, currently there are editions for Budgie, COSMIC, GNOME (Silverblue), KDE Plasma (Kinoite) and Sway. Every atomic desktop installation is identical to every other installation of the same version, and it never changes as it is used. The immutable design is intended to make the operating system more stable, less prone to bugs, easier to test and develop, and create a platform for containerized applications as well as container-based software development. Applications and containers are kept separate from the host system. OS updates are fast and there is no installation stage. It is possible to roll back to the previous version of the operating system, if something goes wrong.
The long-term goal for this effort is to transform Fedora Workstation into an image-based system where applications are separate from the OS, and updates are atomic. Fedora developers, Red Hat engineers, along with independent contributors have been developing and/or contributing to software used in the atomic desktops. Such as: OSTree, Wayland, Flatpak, and rpm-ostree support in GNOME Software, etc. Project Atomic added new features like package layering to rpm-ostree and added rpm-ostree support to Anaconda.


### Server
Its target usage is for servers. It includes the latest data center technologies. This edition does not come with a desktop environment, but one can be installed. From Fedora 28, Server Edition will deliver Fedora Modularity, adding support for alternative update streams for popular software such as Node.js and Go.


### IoT
Images of Fedora Linux tailored to running on Internet of Things devices. It supports x86_64, aarch64 and armhfp processors.


### CoreOS
The successor of Fedora Atomic Host (Project Atomic) and Container Linux after Fedora 29, it provides a minimal image of Fedora Linux which includes just the bare essentials. This is not to be confused with Fedora Core. It is meant for deployment in cloud computing. It provides Fedora CoreOS images which are optimized minimal images for deploying containers. CoreOS replaced the established Container Linux when it was merged with Project Atomic after its acquisition by Red Hat in January 2018.


### Labs
Similar to Debian blends, the Fedora Project also distributes custom variations of Fedora Linux called Fedora Labs. These are built with specific sets of software packages, targeting specific interests such as gaming, security, design, robotics, and scientific computing (that includes SciPy, Octave, Kile, Xfig and Inkscape).
The Fedora AOS (Appliance Operating System) was a specialized spin of Fedora Linux with reduced memory footprint for use in software appliances. Appliances are pre-installed, pre-configured, system images. This spin was intended to make it easier for anyone (developers, independent software vendors (ISV), original equipment manufacturers (OEM), etc.) to create and deploy virtual appliances.


### Architectures
x86-64 and ARM AArch64 are the primary architectures supported by Fedora. As of release 38, Fedora also supports IBM Power64le, IBM Z ("s390x"), MIPS-64el, MIPS-el and RISC-V as secondary architectures.
Fedora 28 was the last release that supported ppc64 and users are advised to move to the little endian ppc64le variant. Fedora 36 was the last release with support for ARM-hfp.


### Alternatives
The Fedora Project also distributes several other versions with fewer use cases than mentioned above, like network installers and minimal installation images. They are intended for special cases or expert users that want to have custom installations or configuring Fedora from scratch.
In addition, all acceptable licenses for Fedora Linux (including copyright, trademark, and patent licenses) must be applicable not only to Red Hat or Fedora, but also to all recipients downstream. This means that any "Fedora-only" licenses, or licenses with specific terms that Red Hat or Fedora meets but that other recipients would not are not acceptable (and almost certainly non-free, as a result).


## History

The name of Fedora derives from the original "Fedora Linux", a volunteer project that provided extra software for the Red Hat Linux distribution, and from the characteristic fedora hat used in Red Hat's "Shadowman" logo. Warren Togami began Fedora Linux in 2002 as an undergraduate project at the University of Hawaii, intended to provide a single repository for well-tested third-party software packages so that non-Red Hat software would be easier to find, develop, and use. The key difference between Fedora Linux and Red Hat Linux was that Fedora's repository development would be collaborative with the global volunteer community. The original Fedora Linux was eventually absorbed into the Fedora Project, carrying with it this collaborative approach. The Fedora Project is sponsored primarily by Red Hat with additional support and sponsors from other companies and organizations.
Fedora Linux, then known as "Fedora Core", was a fork of Red Hat Linux launched in 2003, when Red Hat Linux was discontinued so the team could focus on their paid version for servers: Red Hat Enterprise Linux. Red Hat Enterprise Linux was to be Red Hat's only officially supported Linux distribution, while Fedora was to be a community distribution. Red Hat Enterprise Linux branches its releases from versions of Fedora.
Before Fedora 7, Fedora Linux was called Fedora Core after the name of one of the two main software repositories - Core and Extras. Fedora Core contained all the base packages that were required by the operating system, as well as other packages that were distributed along with the installation CD/DVDs, and was maintained only by Red Hat developers. Fedora Extras, the secondary repository that had been included since Fedora Core 3, was community-maintained and not distributed along with the installation CD/DVDs. Upon the release of Fedora 7, the distinction between Fedora Core and Fedora Extras was eliminated.
Since the release of Fedora 21, as an effort to bring modularization to the Fedora distribution and make development more agile, three different versions are available: Workstation, focused on the personal computer, Server and Atomic for servers, Atomic being the version meant for cloud computing.
Fedora is a trademark of Red Hat, Inc. Red Hat's application for trademark status for the name "Fedora" was disputed by Cornell University and the University of Virginia Library, creators of the unrelated Fedora Commons digital repository management software. The issue was resolved and the parties settled on a co-existence agreement that stated that the Cornell-UVA project could use the name when clearly associated with open source software for digital object repository systems and that Red Hat could use the name when it was clearly associated with open source computer operating systems.
In April 2020, project leader Matthew Miller announced that Fedora Workstation would be shipping on select new ThinkPad laptops, thanks to a new partnership with Lenovo.
Framework officially supports Fedora Workstation on their laptops.


## Development and community


Development of the operating system and supporting programs is headed by the Fedora Project, which is composed of a community of developers and volunteers, and also Red Hat employees. The council is the top-level community leadership and governance body. Other bodies include the Fedora Engineering Steering Committee, responsible for the technical decisions behind the development of Fedora, and Fedora Mindshare Committee which coordinates outreach and non-technical activities, including representation of Fedora Worldwide e.g.: Ambassadors Program, CommOps team and Marketing, Design and Websites Team.


## Releases


Fedora has a relatively short life cycle: version X is supported only until 1 month after version X+2 is released and with approximately 6 months between most versions, meaning a version of Fedora is usually supported for at least 13 months, possibly longer. Fedora users can upgrade from version to version without reinstalling.
The current release is Fedora 42, which was released on 15 April 2025.


### Rawhide
Rawhide is the development tree for Fedora. This is a copy of a complete Fedora distribution where new software is added and tested, before inclusion in a later stable release. As such, Rawhide is often more feature rich than the current stable release. In many cases, the software is made of CVS, Subversion or Git source code snapshots which are often actively developed by programmers. Although Rawhide is targeted at advanced users, testers, and package maintainers, it is capable of being a primary operating system. Users interested in the Rawhide branch often update on a daily basis and help troubleshoot problems. Rawhide users do not have to upgrade between different versions as it follows a rolling release update model.


## See also


ABRT
Fedora Media Writer
List of Linux distributions § RPM-based


## References



## External links

