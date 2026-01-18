# SolidWorks CAD Standards

## File Naming Conventions
General Format:
```
[DESCRIPTION]_[VERSION].[EXTENSION]
```
Use UpperCamelCase for [DESCRIPTIONS]  
Use 2 digits for [VERSION]  
### Examples
- `BracketMounting_v01.SLDPRT`
- `HousingAssembly_v22.SLDASM`
- `BracketMounting_v01.SLDDRW`

## Hardware & Fastener Standards

### Approved Fasteners
Only M2, M3, M4, and M5 metric fasteners are permitted in all designs.  
IF a fastner is a screw, use philips.  
IF a custom fastner is designed, use that instead.  

NOTE:
when making custom fastners DO NOT SAVE THEM AS TOOLBOX PARTS, save them as a custom part. This allows them to render properly upon loading on a different computer
## CAD Configuration Standards

### Units
**All projects use MMGS (millimeter, gram, second)**

## Quality Checks Before Commit

- [ ] File naming follows convention
- [ ] No external references broken
- [ ] Files saved in correct directory
- [ ] Only approved M2-M5 fasteners used

---

