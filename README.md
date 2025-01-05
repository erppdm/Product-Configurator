The **SolidWorks Product Configurator** offers an efficient and flexible solution for automating the creation and management of CAD models, drawings and product configurations. It has been designed for seamless integration into company workflows and simplifies and accelerates the design process through to data transfer to the ERP system.

**SolidWorks Product Configurator** is a powerful and lightweight solution for the automatic:
- Creation of products and their variants in CAD
- Creation of 3D models and drawings
- Creation of neutral formats in 3D/2D
- Creation and management of BOMs
- Management of configured products

The configurator was designed in such a way that the entire logic for creating the models and drawings can be implemented in Excel. The configuration in SolidWorks is done only via VBA macro, which allows access to all functions of the SolidWorks API.
- Easy customization to company-specific specifications and workflows through VBA macros
- Error reduction by splitting the VBA macros into small, functional blocks
- Creation of models and drawings from scratch without a template possible
- Use of all file formats supported by SolidWorks possible

By using [VBADC](https://github.com/erppdm/VBADC#vbadc), it is possible to reference any DLL in the SolidWorks macro, which can be accessed later by dynamically loaded modules.

Despite the [VBA limitation](https://excel.tips.net/T003174_Maximum_Length_Limit_for_a_Macro.html#:~:text=Excel%20apparently%20has%20a%20limit,say%2C%20a%20dozen%20smaller%20macros.), approximately 90,000 steps can be guaranteed in Excel in the current configurator.

When creating the **Excel Configurators**, the macros are compiled in Excel from an SQL database. This guarantees that all configurators always work with the latest macros.

There are no limits to the use of the configurator. Any number of SolidWorks CAD instances are possible in the network or on one computer. The only limitation is the hardware or the quantity of software licenses.

A web interface is available for remote control of the configurators. The complete logic is already integrated in the server, so that simple modifications are possible. The server is programmed in [Blazor](https://github.com/dotnet/aspnetcore/tree/main/src/Components#blazor).

The configurator can be integrated into [PDM-ERP Inegration](https://github.com/erppdm/PDM-ERP-Integration?tab=readme-ov-file#introduction) to transfer configured models and drawings automatically into the PDM and synchronize data with the ERP system.

In summary, the **SolidWorks Product Configurator* combines flexibility, efficiency, and seamless integration to streamline CAD creation and ensure compatibility with modern workflows and systems.
