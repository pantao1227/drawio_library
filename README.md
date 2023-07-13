# drawio_library

## Logic Items
### INV
```text
oxooooo
ooooooo
xxoooxx
ooooooo
oxooooo
```
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
## AND
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
