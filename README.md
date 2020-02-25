# ManulabHMIWeb
@author Hans-Christian Ringstad

This project was made to be used in the Bachelor Thesis Manulab spring 2020, it is the Human Machine Interface and will also be used as Web client to order products. This project was made in Movicon.NExT. 

Movicon.NExT will be able communicate directly with sysmac studio.

Variables to transfer: 
- orderReceived (BOOL)
- productID (INT, can be made STRING)
- name (STRING)
Movicon import code: 
HOST	NAME	DATATYPE	ADDRESS	COMMENT	TAGLINK	RW	POU
	customerOrder.orderReceived	BOOL			TRUE	RW	
	customerOrder.productID	INT			TRUE	RW	
	customerOrder.name	STRING(256)			TRUE	RW	

