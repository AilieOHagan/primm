# PRIMM: Pre-Ingest Metadata Modifier

PRIMM was created to prepare Standard Dublin Core XML metadata exported from ContentDM, for ingest into the digital preservation system, Preservica. 

## Features

PRIMM splits collections-level metadata exported from ContentDM, into multiple page-level metadata files, compatible with Preservica. 

It does this by working in three ways: 
 - Restructures the metadata framework from RDF to OAI (this ensures metadata can be edited in Preservica post-ingest)
 - Converts XML to OPEX (required for successful ingest into Preservica) 
 - Splits into page-level metadata files (useful for retaining metadata notes or rights information for specific pages).

This tool is particularly useful for collections containing multiple items, or manuscripts with multiple pages.  

## How do I use it?

1. Your PRIMM file will save any generated .opex metadata files into its same location, so you may wish to create a folder for this purpose. For example, you could create a folder called, e.g. “PRIMM” and save your .jar file inside. 
2. Paste any xml file(s) for processing into this folder. 
3. Open the primm jar and in the dialogue box, enter the title of the XML file to be processed. Click “Run”. 
4. In a few seconds multiple OPEX files will appear alongside the original XML. 
5. You can move these metadata files to sit alongside their corresponding digital assets in preparation for ingest into Preservica.

-----

![image](https://github.com/mohagan9/primm/assets/30199063/10c3923f-14dd-405a-9dcc-cf04277efd95)


1. Your PRIMM.jar file will save any generated .opex metadata files into its same location, so you may wish to create a folder for this purpose. For example, you could create a folder called, e.g. “PRIMM” and save your PRIMM.jar file inside. 

![image](https://github.com/mohagan9/primm/assets/30199063/6041b6ba-6837-4caa-9373-a09a742c9100)


2.Paste any xml file(s) for processing into this folder. 

![image](https://github.com/mohagan9/primm/assets/30199063/996dfc61-dd98-4e7f-a30c-220c17cb80f4)


3. Open PRIMM-1.0.0.jar and in the dialogue box, enter the title of the XML file to be processed. Click “Run”. 

![image](https://github.com/mohagan9/primm/assets/30199063/9b3f0a42-4136-4750-96ec-73c480fc4766)


4. In a few seconds multiple OPEX files will appear alongside the original XML... 

![image](https://github.com/mohagan9/primm/assets/30199063/a619bf88-f69b-4153-9adc-ac78bea0228d)


5. You can move these metadata files to sit alongside their corresponding digital assets.

![image](https://github.com/mohagan9/primm/assets/30199063/500e153f-bd42-4190-9710-1e5d518f1ff8)

**Note:** As a final step, insert the file format into the .opex filename to match the format of your digital assets, e.g. Test.jpg.opex (you can use a tool such as Bulk Rename Utility to do this). Your digital assets and metadata are now ready for upload and ingest into Preservica.

From this:
![image](https://github.com/mohagan9/primm/assets/30199063/1fc84dec-b645-4f51-8cc9-7b2c4241082a)

To this:
![image](https://github.com/mohagan9/primm/assets/30199063/5bb855d8-6db4-4fac-a990-859385fadf50)

*See the example folder for the full output.*
