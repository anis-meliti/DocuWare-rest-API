[Typedoc project reference documentation](../README.md) / [Modules](../modules.md) / [types/DW_Rest](../modules/types_dw_rest.md) / [DWRest](../modules/types_dw_rest.dwrest.md) / IPage

# Interface: IPage

[types/DW_Rest](../modules/types_dw_rest.md).[DWRest](../modules/types_dw_rest.dwrest.md).IPage

DocuWare Page Model

**`interface`** IPage

## Hierarchy

* [*ILinkModel*](types_dw_rest.dwrest.ilinkmodel.md)

  ↳ **IPage**

## Table of contents

### Properties

- [Data](types_dw_rest.dwrest.ipage.md#data)
- [Links](types_dw_rest.dwrest.ipage.md#links)
- [PageNum](types_dw_rest.dwrest.ipage.md#pagenum)

## Properties

### Data

• **Data**: { `ContentArea`: { `Height`: *number* ; `Left`: *number* ; `Top`: *number* ; `Width`: *number*  } ; `DpiX`: *number* ; `DpiY`: *number* ; `Height`: *number* ; `LowQualitySize`: *number* ; `RenderedImageFormat`: *string* ; `TileSize`: *number* ; `Width`: *number*  }

#### Type declaration:

Name | Type |
------ | ------ |
`ContentArea` | { `Height`: *number* ; `Left`: *number* ; `Top`: *number* ; `Width`: *number*  } |
`DpiX` | *number* |
`DpiY` | *number* |
`Height` | *number* |
`LowQualitySize` | *number* |
`RenderedImageFormat` | *string* |
`TileSize` | *number* |
`Width` | *number* |

Defined in: types/DW_Rest.d.ts:177

___

### Links

• `Optional` **Links**: [*ILink*](types_dw_rest.dwrest.ilink.md)[]

Inherited from: [ILinkModel](types_dw_rest.dwrest.ilinkmodel.md).[Links](types_dw_rest.dwrest.ilinkmodel.md#links)

Defined in: types/DW_Rest.d.ts:10

___

### PageNum

• **PageNum**: *number*

Defined in: types/DW_Rest.d.ts:176
