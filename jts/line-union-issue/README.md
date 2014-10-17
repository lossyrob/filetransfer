This folder contains two geometries in WKT.

The first one, WASHINGTON-DC.wkt, is a MultiLineString representing all of the trip lines contained inside the Washington DC GTFS data. It is a valid MultiLineString.

The second, WASHINGTON-DC-unioned.wkt, is the resulting MultiLineString when `union()` is called on the first MultiLineString. It produces and invalid MultiLineString.