# libedid

#Libedid plans
Task 1: Create a library out of the edid-decode source: option: make library or make binary
Task 2: Add high-level wrapper APIs as below (expose it in header file)
	basic_display_info() => Break it into individual APIs like Serial no, Product, Manufacturer etc
	colorimetry_info() 
	hdr_info() -> populate HDR info/metadata in human readable format
	supported_colorspaces()
Task 3: Define the structure with relevant info per entity like colorimtery, hdr etc
Task 4: Create a test app to use high level wrapper APIs with defined structure, library parses the EDID, fills the structure and returns the same to client

Note: This is an ealry plan and can always be expanded with common understanding amount people around it
