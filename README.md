# Summer of Code @ Software Heritage
Report for Google Summer of Code '22 Project @ Software Heritage

| Project Details|  |
|---	|---	|
|Initial Proposal|  [Mine Information from Archived Content](https://vsatvik.in/assets/pdf/GSoC'22-SWH-SatvikVemuganti-Mine%20Information%20from%20Archived%20Content-SUBMIT.pdf)|
|Repository|[swh-indexer](https://forge.softwareheritage.org/source/swh-indexer/)|
|Mentors| [Stefano Zacchirolli](https://github.com/zacchiro), [Valentin Lorentz](https://github.com/Progval), and [Kumar Shivendu](https://github.com/kshivendu)|
|Contributions| [swh-indexer](https://github.com/SoftwareHeritage/swh-indexer/commits?author=VickyMerzOwn)|
|Duration| 3 months (13-06-2022 to 12-09-2022)|

### About the SWH Project
Software Heritage is a far-reaching Open Source-Research project that, at its core, archives software source code, hereby keeping it from becoming extinct. As a part of this, Software Heritage’s indexer extracts from source code repositories, certain metadata ranging from simple information (eg. project name or hosting place) to more substantial ones like the entity behind the project, its license, etc. According to Software Heritage, metadata is the information it collects and extracts that provides additional information on source code. This project aims to contribute to the sharing phase where help is needed to organize contents to build efficient indexing and querying mechanisms and to develop applications for specific domains.

### Contributions
The search feature of Software Heritage's universal archive of software source code offers searching via URL or through package metadata.
As part of GSoC'22, I worked on adding mappings to Packagist (composer.json), NuGet (*.nuspec), and dart (pubspec.yaml) packages. In total, these span more than 750k packages. Additionally, I am currently working on a mapping for Cocoapods (*.podspec) packages. Please find all my contributions [here](https://forge.softwareheritage.org/p/VickyMerzOwn/). Here is a summary:
- Indexer for Packagist (composer.json) -> [D8047](https://forge.softwareheritage.org/D8047) (Related Task: [T4357](https://forge.softwareheritage.org/T4357))
- Metadata Indexer for Pub (pubspec.yaml) ([D8079](https://forge.softwareheritage.org/D8079)) (Related Task: [T4376](https://forge.softwareheritage.org/T4376))
- Add NuGet Mapping (*.nuspec) ([D8144](https://forge.softwareheritage.org/D8144)) (Related Task: [T4392](https://forge.softwareheritage.org/T4392))

### Future Work
Continuing from here, I am very excited to continue contributing to Open Source. Software Heritage is on a great and important mission that I'm privileged to be a part of and deeply excited to continue contributing to. Here are some future aspects to this project:
- Writing a metadata indexer for Cocoapods packages (*.podspec) (Related Task: [T4437](https://forge.softwareheritage.org/T4437))
- Extend the coverage of supported metadata to all [Libraries.io](https://libraries.io)-indexed package managers
- Possibly use [Bibliothecary](https://github.com/librariesio/bibliothecary/) to extract package metadata

Parallel to my coding journey, I have written up 2 blogs to summarize my learning curve and the state of my project at the time. My mentors were kind to review them before they were published.
- [Software Heritage](https://vsatvik.in/project/blog/2022/05/25/software-heritage)
- [My contribution so far](https://vsatvik.in/project/blog/2022/07/12/software-heritage-my-journey-so-far)

Overall, it was a wonderful experience working with knowledgeable mentors and learning from them. Looking forward to continue learning with them.
