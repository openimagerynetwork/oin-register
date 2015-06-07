# Open Imagery Network

### What is OIN?

Open Imagery Network (OIN) is a discoverable network of openly licensed imagery. Contributors to OIN make imagery and its associated metadata available under a [common license](https://creativecommons.org/licenses/by/4.0/). Information about the location and the storage type for contributed imagery and metadata can be found in [this register](https://raw.githubusercontent.com/openimagerynetwork/oin-register/master/master.json). Anyone can access and read imagery found from this register, enabling tooling to be built that searches across all participating open imagery data.

Open Imagery Network connects satellite and aerial imagery providers, humanitarian relief efforts, cloud hosting companies, uav and balloon mapping enthusiasts, governments and NGOs, mapping companies, and anyone else who is producing, hosting, and using aerial imagery.

### Why does OIN exist?

Each day more and more organizations are using imagery, or the data generated via the analysis of that imagery, in their operations. Open access to imagery and geospatial data is a foundational part of the suite of technical and community tools focused on improving the operational efficiency and effectiveness of many activities including environmental sustainability, humanitarian and disaster response, free speech, civic activism and public health. 

Imagery is valuable, and is a resource worth sharing. OIN's mission is to develop a community around the sharing, use and hosting of open imagery. Having a network of openly licensed imagery will enable innovative approaches in the consumption and analysis of imagery, and will give those who collect imagery an easy way to share that valuable resource. With OIN, individuals and organizations are able to access, process and analyze open imagery available for anywhere on earth within an ecosystem of tools built to make its use and access possible by both technical and non-technical users.

### What is OIN not?

Open Imagery Network allows access to open imagery without requiring one entity to host it all. The Open Imagery Network is simply a way of discovering the imagery that is available on the network, and does not provide hosting of imagery data. If you have imagery that you would like to contribute to OIN, but cannot provide hosting, please contact the [OpenAerialMap team](https://groups.google.com/a/hotosm.org/forum/#!forum/openaerialmap).

Open Imagery Network will not provide a catalog and compelling mapping interface to all the imagery in the network. It is only the core technology and open standards that define a machine-readable structure of the data. Tooling that provides searchable catalogs, image processing and visualizations of the data are outside the scope of Open Imagery Network; however, tooling that is based on Open Imagery Network is already being developed, such as the Humanitarian OpenStreetMap Team's [OpenAerialMap](https://github.com/hotosm/OpenAerialMap).

### Licensing

![CC-BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)

All imagery contained in OIN is licensed [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/), with attribution as *contributors of Open Imagery Network*.

### Imagery Format

All imagery accessed through OIN is in RGB GeoTiff format, with a corresponding metadata file to provide the users of OIN information about the imagery. The specification for the metadata can be [found here](https://github.com/openimagerynetwork/oin-metadata-spec).

### How to contribute to OIN

1. Create an object store. This can be Amazon S3, Microsoft Azure, or Google Cloud Storage.
  - Follow storage requirements about your storage permissions and adding imagery. 
  - Adhere to guidelines on `.tif` files and matching metadata files. 

2. Make a pull request to the `register` with your object store information. 

3. Agree to [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. This will be similar to OpenStreetMap. There will be a single license for use. Contributors to OIN will be listed for contribution to the network. By making a pull request to the `register` you are agreeing to the license.
