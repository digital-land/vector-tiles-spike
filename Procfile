web: curl -o conservation-area.mbtiles https://vector-tile-spike.s3.eu-west-2.amazonaws.com/conservation-area.mbtiles; curl -o brownfield-land.mbtiles https://vector-tile-spike.s3.eu-west-2.amazonaws.com/brownfield-land.mbtiles; curl -o local-authority-district.mbtiles https://vector-tile-spike.s3.eu-west-2.amazonaws.com/local-authority-district.mbtiles; curl -o parish.mbtiles https://vector-tile-spike.s3.eu-west-2.amazonaws.com/parish.mbtiles; datasette serve local-authority-district.mbtiles parish.mbtiles brownfield-land.mbtiles conservation-area.mbtiles -m metadata.json --plugins-dir=plugins/ -h 0.0.0.0 -p $PORT --cors