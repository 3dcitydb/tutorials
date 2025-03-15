Hands-on Tutorial for 3DCityDB Beginners
==================================

> [!NOTE]
> This repository hosts tutorials for the 3DCityDB v4. Although 3DCityDB v5 is now available, 3DCityDB v4
> remains stable and operational. However, it is in **maintenance mode**, meaning no significant new features are
> planned, though existing bugs will continue to be addressed. Development is now focused on 3DCityDB v5, and we recommend
> upgrading to benefit from new features and improvements. Please refer to the [3DCityDB v5 user manual](https://3dcitydb.github.io/3dcitydb-mkdocs/)
> for more information.

This tutorial gives a step-by-step instructions about the download and installation of the software, 
the import of CityGML datasets, the export and 3D visualization of 3D city models in a web browser. 
Please note that this tutorial does not provide an extensive explanation of the 3DCityDB sofware package itself. 
If you need more details about 3DCityDB, please refer to the 
[comprehensive technical documentation](https://github.com/3dcitydb/3dcitydb/tree/master/Documentation) 
instead. 

The tutorial includes an explanation on the installation of PostgreSQL/PostGIS and on setting up the corresponding database accounts. 
Please note that there also exists a simplified way of installation using the virtualization technology [Docker](https://www.docker.com/) and the [3DCityDB Docker images](https://github.com/tum-gis/3dcitydb-docker-postgis). 

Structure
-------
<p align="center">
<img src="images/img1.png" width="800" />
</p>

Copyright
-----------------------------------

Copyright © 2016-2018 [Chair of Geoinformatics, Technical University of Munich (TUMGI)](https://www.gis.bgu.tum.de/). All rights reserved.

License
-------
This tutorial is licensed under the [ Creative Commons License CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/legalcode). According to CC BY-NC-SA 3.0 permission is granted to share this document, i.e. copy and redistribute the material in any medium or format, and to adapt it, i.e. remix, transform, and build upon the material under the following conditions:

1. **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use. 
2. **NonCommercial** — You may not use the material for commercial purposes. 
3. **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original. 
4. **No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits. 

A clarification concerning point 2: **non-commercial usage** means that this hands-on tutorial is not allowed to be used in a commercial training course on the 3DCityDB. It is, however, allowed to use this hands-on tutorial for learning about 3DCityDB within commercial companies or projects.

Main authors
-----------------------------------

* Zhihang Yao
<br>[virtualcitySYSTEMS GmbH](https://www.virtualcitysystems.de/)


* Son H. Nguyen and Thomas H. Kolbe
<br>[Chair of Geoinformatics, Technical University of Munich](https://www.gis.bgu.tum.de/)


More information
----------------
[OGC CityGML](http://www.opengeospatial.org/standards/citygml) is an open data model and XML-based format for the storage and exchange of semantic 3D city models. It is an application schema for the [Geography Markup Language version 3.1.1 (GML3)](http://www.opengeospatial.org/standards/gml), the extendible international standard for spatial data exchange issued by the Open Geospatial Consortium (OGC) and the ISO TC211. The aim of the development of CityGML is to reach a common definition of the basic entities, attributes, and relations of a 3D city model.

CityGML is an international OGC standard and can be used free of charge.
