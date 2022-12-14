# Global Elevation

Get the elevation for every point on earth

## Install

```bash
npm i global-elevation 
```

## Usage

```javascript
const { ETOPO5 } = await import('global-elevation');
let etopo5 = new ETOPO5();
let elevation = await etopo5.getElevation(13.4083, 52.5186);
```

## Sources:

| implemented | name       | source                                                                                |
| ----------- | ---------- | ------------------------------------------------------------------------------------- |
| ✅           | ETOPO1     | [ETOPO1](https://www.ngdc.noaa.gov/mgg/global/)                                       |
| ✅           | ETOPO5     | [ETOPO5](https://registry.opendata.aws/copernicus-dem/)                               |
| -           | Copernicus | [Copernicus](https://registry.opendata.aws/copernicus-dem/)                           |
| -           | CEDTM      | [CEDTM - Continental Europe Digital Terrain Model](https://zenodo.org/record/4724549) |
| -           | NASADEM    | [NASADEM_HGT](https://e4ftl01.cr.usgs.gov/MEASURES/NASADEM_HGT.001/2000.02.11/)       |
