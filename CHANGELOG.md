Change Log
==========


### Ver. 1.4.6 (08/22)
- Min packet len to decode - 31 bytes (insted of 32)
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
- Fix Rvt decoding (remove hard coded write to disk)

### Ver. 1.1.0
- Add plugin support for MISB806 user defined metadata

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
- Fix some encodings to 16 bit instesd of 32 bit
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
