Change Log
==========
### Ver. 2.3.0 (21/03/24)
- Remove length from VMTI Location (tag 17)
- Remove length from VMTI Velocity and Acceleration DLP 

### Ver. 2.2.1 (10/03/23)
- Generic Flag Data (tag47) Versions 13 through 16 of ST 0601 unintentionally inverted the column definitions; 

### Ver. 2.2.0 (07/11/23)
- Bump the version to 2.2.0 to sync with the native library

### Ver. 1.7.3 (24/10/23)
- Add VMTI timestamps types (integer, string, datetime)

### Ver. 1.7.2 (12/10/23)
- Fix long VMTI tracker (over 14 items)

### Ver. 1.7.1 (16/07/23)
- Fix BER-OID Encoding/Decoding for VMTI Target ID

### Ver. 1.7.0 (01/02/23)
- Add VChip
- Option to read license info from the environmental variables.

### Ver. 1.6.1 (8/01/23)
- Update device id

### Ver. 1.5.2 (22/08/22)
- Fix mix/max range (4294967294/4294967295) for some tags

### Ver. 1.5.2 (14/08/22)
- Fix VMTI target Id

### Ver. 1.5.1 (8/08/22)
- Add tag 122, 138, 139

### Ver. 1.5.0 (06/08/22)
- Add tags 115, 116, 121, 128

### Ver. 1.4.6 (08/22)
- Min packet len to decode - 31 bytes (instead of 32)
- Support 3 and 4 bytes klv len

### Ver. 1.4.5 (30/05/22)
- Add ConvertTargetCenterPoint
- Fix Tag 110

### Ver. 1.4.4 (19/05/22)
- Fix Unsigned/signed range exception

### Ver. 1.4.3 (12/05/22)
- Add helper funcitons to MISB903

### Ver. 1.4.2 (25/02/22)
- Add Tag 102 VObject
- Fix  Correction Offset ToDetailed exception

### Ver. 1.4.1 (01/02/22)
- Add KeepTimeTagEmpty property

### Ver. 1.4.0 (16/12/21)
- Fix Vmti target pack encoding. 
- Add support for target color additional format (as either string or number)
- Remove vTargetPack tag. use data directly. vTargetPack is still supported for backward compatibility, will be removed later
- Target color Detailed show html color
- Add Tracker ID 16 byte guid

### Ver. 1.3.0 (02/12/21)
- Set current time (tag 2) during packet encoding, if not provided or UpdateTimeToCurrentTime property set to true

### Ver. 1.2.3 (01/12/21)
- Add native library mode

### Ver. 1.2.2 (04/11/21)
- Fix higher tags in user defined plugin

### Ver. 1.2.1 (01/11/21)
- Fix long user defined data buffer

### Ver. 1.2.0
- Add Linux support for node string generation

### Ver. 1.1.1
- Fix Rvt decoding (remove hardcoded  write to disk)

### Ver. 1.1.0
- Add plugin support for MISB806 user-defined metadata

### Ver. 1.0.14
- Fix activation (13/05/21)

### Ver. 1.0.13
- Fix negative byte

### Ver. 1.0.12
- Allow integers in addition to float for some tags

### Ver. 1.0.11
- Add License verifier

### Ver. 1.0.10
- Fix Big Endian Unicode in UTF-16

### Ver. 1.0.9
- Add missing values to FilterSpecialValues

### Ver. 1.0.8
- Add float support for special values
- Fix some encodings to 16 bit instead of 32 bit
- Add ElevationAngle special value

### Ver. 1.0.7
- Fix Tag 6, 7 special value
- Fix casting for 32 bit special values

### Ver. 1.0.6
- Fix Tag 20 ( Sensor Relative Roll Angle) validation

### Ver. 1.0.5
- Enable FIPS Compliant authorization

### Ver. 1.0.4.1
- Add Id

### Ver. 1.0.4
- Add Encode 1204
- Add OrderByTags
- Fix short special value

### Ver. 1.0.3
- Fix checksum and Last nested KlvItems

### Ver. 1.0.2
- Fix checksum with start offset

### Ver. 1.0.1
- Add RAW Klv decoding and encoding
- Checksum validation
- Partial RAW Klv processing

### Ver. 1.0.0
- Initial version
