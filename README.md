
# Sierra Lobo KiCad Libraries

## Import Instructions

1. Download a local copy of this repository.
2. Open KiCad, under *Preferences* ribbon, select *Configure Paths*
3. Add a path 
>`Name : KICAD7_SLI_LIBS`
>`Path : A:\\Path\to\local\copy`
4. Under *Preferences* ribbon, select *Manage Symbol Libraries*
5. Add a **global** symbol library
>`Nickname     : "SierraLobo"`
>`Library Path : "${KICAD7_SLI_LIBS}/symbols/SierraLobo.kicad_sym"`
4. Under *Preferences* ribbon, select *Manage Footprint Libraries*
5. Add a **global** footprint library
>`Nickname   : SierraLobo`
>`Library Path : ${KICAD7_SLI_LIBS}/symbols/SierraLobo.kicad_sym`