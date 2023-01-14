# Zilo
Javascript framework to make stuff easier

## Installation
```
npm i zilo
```

## Usage
Import it
```
import zilo from 'zilo'
```

### Text
Reverse
```
zilo.text.reverse('Hello')
```

Capitalize
```
zilo.text.capitalize('Hello')
```

Encode Binary
```
zilo.text.encodeBinary('Hello')
```

Decode Binary
```
zilo.text.decodeBinary('00001')
```

### Color
RGB to HEX
```
zilo.color.rgbToHex(0, 45, 65)
```

All available color conversions
```
zilo.color.rgbToHex()
zilo.color.rgbaToHex()
zilo.color.hexToRgb()
zilo.color.rgbToHsl()
zilo.color.rgbaToHsla()
zilo.color.hslToRgb()
zilo.color.hslaToRgba()
```