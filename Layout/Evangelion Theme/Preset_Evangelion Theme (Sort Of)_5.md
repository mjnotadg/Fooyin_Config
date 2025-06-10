### Header

- **Simple header**: [Unchecked]
- **Show cover**: [Checked]
- **Override height**: 50

**Title**:  
`<b><sized=2>$if2(%album%,Unknown Album)`

**Subtitle**:  	
`<sized=0.5>$if2(%albumartist%,Unknown Artist)`

**Side**:  
**Info**:  
`<sized=-1>[%genres% | ]%trackcount% $ifgreater(%trackcount%,1,Tracks,Track) | %playtime% | %year%`

---

### 2025-06-11_01-00_1.png - Subheaders

- **Override height**: 20 [Unchecked]

**Subheaders**:  

**Left-aligned**:  
`<b><sized=2>$ifgreater(%disctotal%,1,Disc #%disc%)`

**Right-aligned**:  
`$ifgreater(%disctotal%,1,%playtime%)`

---

### 2025-06-11_01-00_2.png - Tracks

- **Override height**: 20

**Left-aligned**:  
` $padright(,$mul($sub(%depth%,1),5))[\[%queueindexes%\]  ][$num(%track%,2).  ]%title%[<alpha=180>  ▪  %uniqueartist%]`

**Right-aligned**:  
`$ifgreater(%playcount%,0,%playcount% |)      %duration% `