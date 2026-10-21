Needed:
- [TV](https://www.mediamarkt.nl/nl/product/_peaq-ptv-24gh-5025c-2025-1882802.html)
- [plexiglass](https://www.gamma.nl/assortiment/kunststofplaat-op-maat/p/C23518744)
- [wood](https://www.gamma.nl/assortiment/bouwhout-vuren-geschaafd-44x69-mm-240-cm/p/B736893)

```sheet
data:
  "0":
    name: sheet1
    freeze: A1
    styles: []
    merges: []
    rows:
      "0":
        cells:
          "0":
            text: Object
          "1":
            text: Notes
          "2":
            text: Rough Price
      "1":
        cells:
          "0":
            text: TV (24 inch)
          "2":
            text: "140"
      "2":
        cells:
          "0":
            text: Plexiglass
          "2":
            text: "22"
      "3":
        cells:
          "0":
            text: Wood
          "2":
            text: "6"
      "6":
        cells:
          "0":
            text: Total price
          "1":
            text: =C2+C3+C4
      "7":
        cells:
          "0":
            text: people
          "1":
            text: "4"
      "8":
        cells:
          "0":
            text: total price per person
          "1":
            text: =B7/B8
      len: 100
    cols:
      "0":
        width: 130
      len: 26
    validations: []
    autofilter: {}
  state:
    sheetName: sheet1
    selector:
      range:
        sri: 2
        sci: 0
        eri: 2
        eci: 0
        w: 0
        h: 0
      ri: 2
      ci: 0

```