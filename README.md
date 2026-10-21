DRAFT

ABAP file formats 
https://github.com/SAP/abap-file-formats




# ABAP CDS File Icons



## Supported Object Types

| Color | Abbr | Object Type | Extension |
|-------|------|-------------|-----------|
| 🟦 | CL | Class | `*.clas.abap` |
| 🟩 | IF | Interface | `*.intf.abap` |
| 🟪 | PR | Program / Report | `*.prog.abap` |
| 🟩 | DS | CDS Data Definition | `*.ddls.asddls` |
| 🟦 | MX | Metadata Extension | `*.ddlx.asddlx` |
| 🟧 | BD | Behavior Definition | `*.bdef.asbdef` |
| 🟦 | SD | Service Definition | `*.srvd.asdsrvd` |
| 🟦 | SB | Service Binding | `*.srvb.asdsrvb` |
| 🟥 | AC | Access Control (DCL) | `*.dcls.asdcls` |
| ⬛ | TB | Database Table | `*.tabl.xml` |
| 🟪 | DE | Data Element | `*.dtel.xml` |
| 🟪 | DM | Domain | `*.doma.xml` |
| 🟥 | ST | Structure | `*.stru.xml` |
| 🟪 | TT | Table Type | `*.ttyp.xml` |
| 🟦 | VW | DDIC View | `*.view.xml` |
| 🟧 | LK | Lock Object | `*.enqu.xml` |
| 🟧 | FG | Function Group | `*.fugr.xml` |
| 🟧 | FM | Function Module | `*.func.abap` |
| 🟩 | NR | Number Range Object | `*.nrob.xml` |
| 🟩 | SH | Search Help | `*.sush.xml`, `*.suso.xml` |
| 🟨 | EI | Enhancement Implementation | `*.enho.xml` |
| 🟫 | ES | Enhancement Spot | `*.enhs.xml` |
| 🟫 | CD | Change Document | `*.chdo.xml` |
| 🟥 | MC | Message Class | `*.msagn.xml` |
| 🟦 | AB | Generic ABAP | `*.abap` |

## Installation

## Development

### Prerequisites

```bash
npm install -g @vscode/vsce
```

### Package

```bash
vsce package
```

### Publish

```bash
vsce publish
```

## License

[MIT](LICENSE)
