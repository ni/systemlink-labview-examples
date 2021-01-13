# Introduction 
This is intended to be a collection of LabVIEW examples to aid with asset management automation.

##Examples
###Update Calibration
Updates an assest's External Calibration information by serial number. This can add new calibration, or simply provide calibration history for the asset.

# Getting Started
##Dependencies
- [JKI JSON Parser](https://www.vipm.io/package/jki_lib_json_serialization/)
- LabVIEW SystemLink Toolkit (written with 2020R3)
- LabVIEW 2020
##Execution
- Open "Update Calibration Example.vi"
- Specify the SystemLink server login information in the "Server", "Username", and "Password" fields
- Set the "Serial Number", "Calibration Date", and "Temperature Sensors" data in the appropriate fields
- Run the VI