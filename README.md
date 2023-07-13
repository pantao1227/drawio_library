# drawio_library

## Logic Items
### BUF
```xml
<shape h="40" w="60" aspect="variable" strokewidth="inherit">
        <connections>
                <constraint x="0" y="0.5" perimeter="1" />
                <constraint x="1" y="0.5" perimeter="1" />
        </connections>
        <background>
                <path>
                        <move x="10" y="0"  />
                        <line x="10" y="20" />
                        <line x="0"  y="20" />
                        <line x="10" y="20" />
                        <line x="10" y="40" />
                        <line x="50" y="20" />
                        <line x="60" y="20" />
                        <line x="50" y="20" />
                        <close />
                </path>
        </background>
        <foreground>
                <fillstroke />
                <stroke />
        </foreground>
</shape>
```
## INV
```xml
<shape h="40" w="60" aspect="variable" strokewidth="inherit">
        <connections>
                <constraint x="0" y="0.5" perimeter="1" />
                <constraint x="1" y="0.5" perimeter="1" />
        </connections>
        <background>
                <path>
                        <move x="10" y="0" />
                        <line x="10" y="20" />
                        <line x="0" y="20" />
                        <line x="10" y="20" />
                        <line x="10" y="40" />
                        <line x="44" y="20" />
                        <close />
                        <move x="50" y="20" />
                        <line x="60" y="20" />
                        <move x="44" y="20" />
                        <line x="44" y="20" />
                </path>
                <fillstroke />
                <stroke />
                <ellipse x="44" y="17" w="6" h="6" />
                <stroke />
        </background>
        <foreground>
        </foreground>
</shape>
```
## AND2
```xml
<shape h="40" w="60" strokewidth="inherit">
        <connections>
                <constraint x="0" y="0.25" perimeter="1" />
                <constraint x="0" y="0.75" perimeter="1" />
                <constraint x="1" y="0.5" perimeter="1" />
        </connections>
        <background>
                <path>
                        <move x="0" y="10" />
                        <line x="10" y="10" />
                        <move x="0" y="30" />
                        <line x="10" y="30" />
                        <move x="50" y="20" />
                        <line x="60" y="20" />
                        <move x="30" y="0" />
                        <line x="10" y="0" />
                        <line x="10" y="40" />
                        <line x="30" y="40" />
                        <arc x="30" y="0" rx="20" ry="20" />
                </path>
        </background>
                <foreground>
                <fillstroke />
                <stroke />
        </foreground>
</shape>
```
## NAND2
```xml
<shape h="40" w="60" strokewidth="inherit">
        <connections>
                <constraint x="0" y="0.25" perimeter="1" />
                <constraint x="0" y="0.75" perimeter="1" />
                <constraint x="1" y="0.5" perimeter="1" />
        </connections>
        <background>
                <path>
                        <move x="0" y="10" />
                        <line x="10" y="10" />
                        <move x="0" y="30" />
                        <line x="10" y="30" />
                        <move x="50" y="20" />
                        <line x="60" y="20" />
                        <move x="24" y="0" />
                        <line x="10" y="0" />
                        <line x="10" y="40" />
                        <line x="24" y="40" />
                        <arc x="24" y="0" rx="20" ry="20" />
                </path>
                <fillstroke />
                <stroke />
                <ellipse x="44" y="17" w="6" h="6" />
                <stroke />
        </background>
        <foreground>
        </foreground>
</shape>
```
## CKLNQ
```xml
<shape h="70" w="60" aspect="variable" strokewidth="inherit">
        <connections>
                <constraint x="0" y="0.142857" perimeter="1" />
                <constraint x="0" y="0.285714" perimeter="1" />
                <constraint x="0" y="0.428571" perimeter="1" />
                <constraint x="0" y="0.7142857" perimeter="1" />
                <constraint x="0.5" y="1" perimeter="1" />
                <constraint x="1" y="0.142857" perimeter="1" />
        </connections>
        <background>
                <rect x="10" y="0" w="40" h="60" />
                <fillstroke />
                <stroke />
                <path>
                        <move x="10" y="10" />
                        <line x="0" y="10" />
                        <move x="10" y="20" />
                        <line x="0" y="20" />
                        <move x="10" y="30" />
                        <line x="0" y="30" />
                        <move x="10" y="50" />
                        <line x="0" y="50" />
                        <move x="30" y="60" />
                        <line x="30" y="70" />
                        <move x="50" y="10" />
                        <line x="60" y="10" />
                        <move x="10" y="45" />
                        <line x="15" y="50" />
                        <line x="10" y="55" />
                </path>
                <fillstroke />
                <stroke />
        </background>
        <foreground>
                <text str="D" x="10.5" y="10" align="left" valign="middle" />
                <text str="SI" x="10.5" y="20" align="left" valign="middle" />
                <text str="SE" x="10.5" y="30" align="left" valign="middle" />
                <text str="CP" x="15.5" y="50" align="left" valign="middle" />
                <text str="Q" x="49.5" y="10" align="right" valign="middle" />
                <save />
                <fontsize size="8" />
                <text str="CD" x="31" y="60.5" align="left" valign="top" />
                <restore />
        </foreground>
</shape>
```
## MUX21
```xml
<shape h="50" w="40" aspect="variable" strokewidth="inherit">
        <connections>
                <constraint x="0" y="0.4" perimeter="1" />
                <constraint x="0" y="0.8" perimeter="1" />
                <constraint x="1" y="0.6" perimeter="1" />
                <constraint x="0.5" y="0" perimeter="1" />
        </connections>
        <background>
                <path>
                        <move x="0" y="20" />
                        <line x="10" y="20" />
                        <move x="0" y="40" />
                        <line x="10" y="40" />
                        <move x="40" y="30" />
                        <line x="30" y="30" />
                        <move x="20" y="15" />
                        <line x="20" y="0" />
                        <move x="10" y="10" />
                        <line x="10" y="50" />
                        <line x="30" y="40" />
                        <line x="30" y="20" />
                        <close />
                        <fillstroke />
                        <stroke />
                </path>
        </background>
        <foreground>
                <text str="0" x="10" y="20.5" align="left" valign="middle" />
                <text str="1" x="10" y="40.5" align="left" valign="middle" />
        </foreground>
</shape>
```
## TAP
```xml
<shape h="20" w="20" aspect="variable" strokewidth="inherit">
        <connections>
                <constraint x="0" y="0.5" perimeter="1" />
        </connections>
        <background>
                <path>
                        <move x="0" y="0" />
                        <line x="0" y="20" />
                        <line x="20" y="10" />
                        <close />
                </path>
                <fillstroke />
                <stroke />
        </background>
        <foreground>
        </foreground>
</shape>
```
## SDFRPQD
```xml
<shape h="70" w="60" aspect="variable" strokewidth="inherit">
        <connections>
                <constraint x="0" y="0.142857" perimeter="1" />
                <constraint x="0" y="0.285714" perimeter="1" />
                <constraint x="0" y="0.428571" perimeter="1" />
                <constraint x="0" y="0.7142857" perimeter="1" />
                <constraint x="0.5" y="1" perimeter="1" />
                <constraint x="1" y="0.142857" perimeter="1" />
        </connections>
        <background>
                <rect x="10" y="0" w="40" h="60" />
                <fillstroke />
                <stroke />
                <path>
                        <move x="10" y="10" />
                        <line x="0" y="10" />
                        <move x="10" y="20" />
                        <line x="0" y="20" />
                        <move x="10" y="30" />
                        <line x="0" y="30" />
                        <move x="10" y="50" />
                        <line x="0" y="50" />
                        <move x="30" y="60" />
                        <line x="30" y="70" />
                        <move x="50" y="10" />
                        <line x="60" y="10" />
                        <move x="10" y="45" />
                        <line x="15" y="50" />
                        <line x="10" y="55" />
                </path>
                <fillstroke />
                <stroke />
        </background>
        <foreground>
                <text str="D" x="10.5" y="10" align="left" valign="middle" />
                <text str="SI" x="10.5" y="20" align="left" valign="middle" />
                <text str="SE" x="10.5" y="30" align="left" valign="middle" />
                <text str="CP" x="15.5" y="50" align="left" valign="middle" />
                <text str="Q" x="49.5" y="10" align="right" valign="middle" />
                <save />
                <fontsize size="6" />
                <text str="CD" x="31" y="60.5" align="left" valign="top" />
                <restore />
        </foreground>
</shape>
```
## OR2
```xml
<shape h="40" w="60" strokewidth="inherit">
        <connections>
                <constraint x="0" y="0.25" perimeter="1" />
                <constraint x="0" y="0.75" perimeter="1" />
                <constraint x="1" y="0.5" perimeter="1" />
        </connections>
        <background>
                <path>
                        <move x="0" y="10" />
                        <line x="14" y="10" />
                        <move x="0" y="30" />
                        <line x="14" y="30" />
                        <move x="50" y="20" />
                        <line x="60" y="20" />
                        <move x="30" y="0" />
                        <line x="10" y="0" />
                        <move x="10" y="40" />
                        <arc x="10" y="0" rx="40" ry="40" />
                        <line x="10" y="0" />
                        <move x="10" y="40" />
                        <line x="30" y="40" />
                        <arc x="30" y="0" rx="20" ry="20" />
                </path>
        </background>
        <foreground>
        <fillstroke />
        <stroke />
        </foreground>
</shape>
```
## NOR2
```xml
<shape h="40" w="60" strokewidth="inherit">
        <connections>
                <constraint x="0" y="0.25" perimeter="1" />
                <constraint x="0" y="0.75" perimeter="1" />
                <constraint x="1" y="0.5" perimeter="1" />
        </connections>
        <background>
                <path>
                        <move x="0" y="10" />
                        <line x="14" y="10" />
                        <move x="0" y="30" />
                        <line x="14" y="30" />
                        <move x="50" y="20" />
                        <line x="60" y="20" />
                        <move x="24" y="0" />
                        <line x="10" y="0" />
                        <move x="10" y="40" />
                        <arc x="10" y="0" rx="40" ry="40" />
                        <line x="10" y="0" />
                        <move x="10" y="40" />
                        <line x="24" y="40" />
                        <arc x="24" y="0" rx="20" ry="20" />
                </path>
                <fillstroke />
                <stroke />
                <ellipse x="44" y="17" w="6" h="6" />
                <stroke />
        </background>
        <foreground>
        </foreground>
</shape>
```
