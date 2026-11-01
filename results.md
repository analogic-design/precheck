# Tiny Tapeout Precheck Results

| Check | Result |
|-----------|--------|
| Magic DRC | ✅ |
| KLayout FEOL | ❌ Fail: Klayout feol failed with 1740 DRC violations |
| KLayout BEOL | ✅ |
| KLayout offgrid | ✅ |
| KLayout pin label overlapping drawing | ❌ Fail: Klayout pin_label_purposes_overlapping_drawing failed |
| KLayout zero area | ✅ |
| KLayout Checks | ✅ |
| Pin check | ❌ Fail: Some ports are missing or have wrong dimensions, see 3 LEF errors and 1 GDS error above |
| Boundary check | ✅ |
| Power pin check | ❌ Fail: VGND does not have a corresponding 'USE GROUND ;' |
| Layer check | ✅ |
| Cell name check | ✅ |
| urpm/nwell check | ✅ |
| Analog pin check | ✅ |
| Verilog syntax check | ✅ |

In case of failure, please reach out on [discord](https://tinytapeout.com/discord) for assistance.