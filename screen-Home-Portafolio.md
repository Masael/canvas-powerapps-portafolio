# Power App Documentation \- Portafolio

| Property                   | Value                                    |
| -------------------------- | ---------------------------------------- |
| App Name                   | Portafolio                               |
| App Logo                   | ![App Logo](resources/applogoSmall.png)  |
| Documentation generated at | domingo, 30 de abril de 2023 02:46 p. m. |

- [Overview](index-Portafolio.md)
- [App Details](appdetails-Portafolio.md)
- [Variables](variables-Portafolio.md)
- [DataSources](datasources-Portafolio.md)
- [Resources](resources-Portafolio.md)
- [Controls](controls-Portafolio.md)

## Home

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![screen](resources/screen.png) | Type: screen |

### Design

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                          |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Height              | Max(App.Height, App.MinScreenHeight)                                                                                                                                                                                                                                                                                                                                                                           |
| ImagePosition       | ImagePosition.Fit                                                                                                                                                                                                                                                                                                                                                                                              |
| LoadingSpinner      | LoadingSpinner.None                                                                                                                                                                                                                                                                                                                                                                                            |
| LoadingSpinnerColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(73, 130, 5, 1)</td></tr><tr><td style="background-color:#498205"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table> |
| Orientation         | If(Self.Width \< Self.Height, Layout.Vertical, Layout.Horizontal)                                                                                                                                                                                                                                                                                                                                              |
| Size                | 1 + CountRows(App.SizeBreakpoints) \- CountIf(App.SizeBreakpoints, Value \>\= Self.Width)                                                                                                                                                                                                                                                                                                                      |
| Width               | Max(App.Width, App.MinScreenWidth)                                                                                                                                                                                                                                                                                                                                                                             |

### Color Properties

| Property | Value                                                                                                                                                                                                                                                                                                                                                                                              |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 148, 110, 0.1)</td></tr><tr><td style="background-color:#00946E"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>White</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property      | Value              |
| ------------- | ------------------ |
| Child Control | ContainerPage      |
| Child Control | LabelMantenimiento |
| Child Control | DataPortafolio     |

## ActivityAreahaN\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                 |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ActivityAreahaN"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ActivityAreahaN"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">38<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Activity Area ha'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 503                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Additionality\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Additionality"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Additionality"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">24<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Additionality<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 369                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Aggregation ID\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                               |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Aggregation ID"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AggregationID"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">3<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Aggregation ID'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">128<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 616                                                                                                                                                        |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 6                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2021\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2023"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2021"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">195<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2023'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 546                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2022\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2024"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2022"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">196<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2024'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 547                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2023\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2025"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2023"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">197<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2025'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 548                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2024\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2026"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2024"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">198<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2026'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 549                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2025\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2027"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2025"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">199<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2027'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 550                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2026\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2028"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2026"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2028'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 551                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2027\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2029"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2027"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">201<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2029'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 552                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2028\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2030"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2028"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">202<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2030'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 553                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2029\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2031"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2029"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">203<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2031'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 554                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2030\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2032"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2030"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">204<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2032'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 555                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ANNUALOMCTSYEAR2031\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUAL O&M CTS 2033"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ANNUALOMCTSYEAR2031"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">205<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ANNUAL O&M CTS 2033'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 7 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 556                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2021\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2023"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2021"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">206<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2023'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 557                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2022\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2024"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2022"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">207<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2024'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 558                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2023\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2025"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2023"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">208<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2025'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 559                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2024\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2026"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2024"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">209<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2026'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 560                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2025\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2027"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2025"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">210<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2027'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 561                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2026\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2028"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2026"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">211<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2028'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 562                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2027\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2029"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2027"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">212<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2029'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 563                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2028\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2030"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2028"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">213<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2030'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 564                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2029\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2031"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2029"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">214<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2031'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 565                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2030\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2032"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2030"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">215<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2032'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 566                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## AOMCDYEAR2031\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCD 2033"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"AOMCDYEAR2031"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">216<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'AO&MCD 2033'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 9, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 567                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ApprovedBuyer\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                               |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Approved Buyer"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ApprovedBuyer"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">17<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Approved Buyer'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 362                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ApprovedbyCounterpartProjectStar\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                                                   |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Approved Counterpart Project Start"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ApprovedbyCounterpartProjectStar"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                               |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">40<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Approved by Counterpart Project Start Date for CAR'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 385                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Biodiversity\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                           |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Biodiversity"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Biodiversity"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">54<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Biodiversity<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 399                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## BLInventoryEndDate\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                      |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"BL Inventory End Date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"BLInventoryEndDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">80<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'BL Inventory End Date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 425                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## BLInventoryStartDate\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                        |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"BL Inventory Start Date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"BLInventoryStartDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">79<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'BL Inventory Start Date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 424                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ButtonInspect

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                                                       |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">NewForm(FormERPAControl); Navigate(ViewData); Set(varDataBit , 1)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                                            |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Inspeccionar"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                          |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Center                                                                                                                                   |
| BorderStyle            | BorderStyle.Solid                                                                                                                              |
| BorderThickness        | 2                                                                                                                                              |
| DisplayMode            | DisplayMode.Edit                                                                                                                               |
| FocusedBorderThickness | 4                                                                                                                                              |
| Font                   | Font.'Open Sans'                                                                                                                               |
| FontWeight             | FontWeight.Semibold                                                                                                                            |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;">40</td></tr></table> |
| Italic                 | false                                                                                                                                          |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>  |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>  |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>  |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>  |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">13<td style="background-color:#ffcccc; width:50%;">15</td></tr></table> |
| Strikethrough          | false                                                                                                                                          |
| Underline              | false                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                           |
| Width                  | 160                                                                                                                                            |
| X                      | 0                                                                                                                                              |
| Y                      | 0                                                                                                                                              |
| ZIndex                 | 1                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                   |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table>           |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>           |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | ColorFade(Self.Fill, \-75%)                                                                                                                                                                                                                                                                                                                                                                                             |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| HoverFill           | ColorFade(RGBA(61, 184, 123, 1), \-50%)                                                                                                                                                                                                                                                                                                                                                                                 |
| PressedBorderColor  | ColorFade(RGBA(61, 184, 123, 1), \-50%)                                                                                                                                                                                                                                                                                                                                                                                 |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                  |
| PressedFill         | ColorFade(RGBA(61, 184, 123, 1), \-30%)                                                                                                                                                                                                                                                                                                                                                                                 |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | Container5 |

## ButtonInspect\_1

| Property                        | Value        |
| ------------------------------- | ------------ |
| ![button](resources/button.png) | Type: button |

### Behavior

| Property | Value                                                                                                                                                                               |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">NewForm(FormCreate); Navigate(CreateData)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property | Value                                                                                                                                                              |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Crear proyecto"<td style="background-color:#ffcccc; width:50%;">"Button"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                                                                                                                                                                     |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | Align.Center                                                                                                                                                                                                                                                                                                              |
| BorderStyle            | BorderStyle.Solid                                                                                                                                                                                                                                                                                                         |
| BorderThickness        | 2                                                                                                                                                                                                                                                                                                                         |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                                                                                                                                                                          |
| FocusedBorderThickness | 4                                                                                                                                                                                                                                                                                                                         |
| Font                   | Font.'Open Sans'                                                                                                                                                                                                                                                                                                          |
| FontWeight             | FontWeight.Semibold                                                                                                                                                                                                                                                                                                       |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                                                                                                                                                            |
| Italic                 | false                                                                                                                                                                                                                                                                                                                     |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                                                                                                                             |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                                                                                                                             |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                                                                                                                             |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                                                                                                                             |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">13<td style="background-color:#ffcccc; width:50%;">15</td></tr></table>                                                                                                                                                                            |
| Strikethrough          | false                                                                                                                                                                                                                                                                                                                     |
| Underline              | false                                                                                                                                                                                                                                                                                                                     |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                                                                                                                                                                      |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If( usuario.Profile = "Admin" Or usuario.Profile = "Director" Or usuario.Profile = "Viewer" Or usuario.Profile = "Desarrollo" Or usuario.Profile = "Originacion", true, false )<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width                  | 160                                                                                                                                                                                                                                                                                                                       |
| X                      | 0                                                                                                                                                                                                                                                                                                                         |
| Y                      | 0                                                                                                                                                                                                                                                                                                                         |
| ZIndex                 | 1                                                                                                                                                                                                                                                                                                                         |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                   |
| ------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -15%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>       |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table>           |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>           |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | ColorFade(Self.Fill, \-75%)                                                                                                                                                                                                                                                                                                                                                                                             |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| HoverColor          | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| HoverFill           | ColorFade(RGBA(61, 184, 123, 1), \-50%)                                                                                                                                                                                                                                                                                                                                                                                 |
| PressedBorderColor  | ColorFade(RGBA(61, 184, 123, 1), \-50%)                                                                                                                                                                                                                                                                                                                                                                                 |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                  |
| PressedFill         | ColorFade(RGBA(61, 184, 123, 1), \-30%)                                                                                                                                                                                                                                                                                                                                                                                 |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | Container4 |

## Buyer\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Buyer"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Buyer"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">66<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Buyer<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 411                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CAROnsiteVerificationn\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                        |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CAR Onsite Verificationn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CAROnsiteVerificationn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">186<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CAR Onsite Verification'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 6 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 537                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CBACalculatorVersion\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                       |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CBA Calculator Version"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CBACalculatorVersion"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">35<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CBA Calculator Version'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 380                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CBAFile\_x0028\_Reference\_x0029\_\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Behavior

| Property | Value                                                                                                                                                                                            |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Launch(DataPortafolio.Selected.'CBA File (Reference)')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property         | Value                                                                                                                                                                      |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CBA File (Reference)"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CBAFile_x0028_Reference_x0029_"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| IsHyperlink      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">36<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CBA File (Reference)'<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 381                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CBCompleted\_x003f\_\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                              |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CB Completed"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CBCompleted_x003f_"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">64<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CB Completed?'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 409                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CBRequestedtoRANDate\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                         |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CB Requested to RAN Date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CBRequestedtoRANDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">63<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CB Requested to RAN Date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 408                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CCBSOnisiteVerificationn\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                         |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CCBS Onisite Verification"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CCBSOnisiteVerificationn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">187<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CCBS Onsite Verification'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 6 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 538                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Confidence\_x0020\_of\_x0020\_Upfron\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                           |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Confidence of Upfront Cost"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Confidence_x0020_of_x0020_Upfron"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">33<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Confidence of Upfront Cost'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 378                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Container4

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height <td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 2                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | ButtonInspect\_1 |
| Parent Control | NavBar           |

## Container5

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.End<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 3                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value         |
| -------------- | ------------- |
| Child Control  | ButtonInspect |
| Parent Control | NavBar        |

## ContainerFooter

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                              |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">60 <td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.End<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| X                    | 0                                                                                                                                                                  |
| Y                    | 0                                                                                                                                                                  |
| ZIndex               | 3                                                                                                                                                                  |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value         |
| -------------- | ------------- |
| Child Control  | NavBar        |
| Parent Control | ContainerPage |

## ContainerHeader

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                       |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">60<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.SpaceBetween<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| X                    | 0                                                                                                                                                                           |
| Y                    | 0                                                                                                                                                                           |
| ZIndex               | 1                                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                    |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>     |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 148, 110, 1)</td></tr><tr><td style="background-color:#00946E"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value         |
| -------------- | ------------- |
| Child Control  | HeaderTitle   |
| Child Control  | HeaderUser    |
| Parent Control | ContainerPage |

## ContainerInferior

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                       |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height -120<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.SpaceBetween<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| X                    | 0                                                                                                                                                                           |
| Y                    | 0                                                                                                                                                                           |
| ZIndex               | 2                                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Child Control  | SearchFilterBar |
| Parent Control | ContainerPage   |

## ContainerPage

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                       |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Stretch<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.SpaceBetween<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| X                    | 0                                                                                                                                                                           |
| Y                    | 0                                                                                                                                                                           |
| ZIndex               | 1                                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | ContainerHeader   |
| Child Control  | ContainerInferior |
| Child Control  | ContainerFooter   |
| Parent Control | Home              |

## Contingencyn\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Contingency"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Contingencyn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">193<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Contingency<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 6 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 544                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Created\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Creado en Portafolio"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Created"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">6<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Creado<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 501                                                                                                                                                        |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CreditType\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Credit Type"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CreditType"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">31<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Credit Type'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 376                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2021\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2022"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2021"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">228<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2022'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 579                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2022\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2023"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2022"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">229<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2023'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 580                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2023\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2024"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2023"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">230<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2024'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 581                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2024\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2025"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2024"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">231<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2025'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 582                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2025\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2026"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2025"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">232<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2026'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 583                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2026\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2027"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2026"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">233<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2027'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 584                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2027\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2028"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2027"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">234<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2028'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 585                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2028\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2029"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2028"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">235<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2029'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 586                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2029\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2030"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2029"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">236<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2030'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 587                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2030\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2031"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2030"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">237<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2031'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 588                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2031\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2032"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2031"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">238<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2032'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 589                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2032\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2033"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2032"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">239<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2033'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 590                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2033\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2034"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2033"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">240<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2034'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 591                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2034\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2033"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2034"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">241<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2035'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 592                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2035\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2036"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2035"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">242<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2036'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 593                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2036\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2037"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2036"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">243<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2037'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 594                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2037\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2038"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2037"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">244<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2038'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 595                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2038\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2039"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2038"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">245<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2039'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 596                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2039\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2040"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2039"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">246<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2040'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 597                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2040\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2041"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2040"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">247<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2041'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 598                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2041\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2042"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2041"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">248<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2042'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 599                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2042\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2043"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2042"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">249<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2043'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 600                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2043\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2044"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2043"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">250<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2044'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 601                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2044\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2045"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2044"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">251<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2045'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 602                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2045\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2046"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2045"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">252<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2046'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 603                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2046\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2047"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2046"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">253<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2047'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 604                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2047\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2048"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2047"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">254<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2048'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 605                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2048\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2049"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2048"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">255<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2049'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 606                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2049\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2050"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2049"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">256<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2050'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 607                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## CRTs2050\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2051"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"CRTs2050"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">257<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'CRTs 2051'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 608                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## DataPortafolio

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![dataTable](resources/dataTable.png) | Type: dataTable |

### Data

| Property   | Value                                                                                                                                                                                                                                                                                                                                                                                                                     |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Items      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If( IsBlank(InpSearch.Text), Sort( Portafolio, Modificado, SortOrder.Descending ), Search( Portafolio, InpSearch.Text, "ProjectID","ProjectName","State","AggregationID","ProjectCounterpart","SafeguardsLead","ProjectAlive_x003f_","ProspectPriority","OriginationStatus" ) )<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| NoDataText | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"-"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                                                                                                                                                                             |

### Design

| Property          | Value                                                                                                                                                                                                                                                                                                                                                                                                                |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle       | BorderStyle.Solid                                                                                                                                                                                                                                                                                                                                                                                                    |
| BorderThickness   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">3<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                                                                                                                                                                          |
| DisplayMode       | DisplayMode.Edit                                                                                                                                                                                                                                                                                                                                                                                                     |
| Font              | Font.'Open Sans'                                                                                                                                                                                                                                                                                                                                                                                                     |
| FontWeight        | FontWeight.Normal                                                                                                                                                                                                                                                                                                                                                                                                    |
| HeadingColor      | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(116, 116, 116, 1)</td></tr><tr><td style="background-color:#747474"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table>  |
| HeadingFill       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(219, 219, 219, 0.64)</td></tr><tr><td style="background-color:#DBDBDB"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table> |
| HeadingFont       | Font.'Open Sans'                                                                                                                                                                                                                                                                                                                                                                                                     |
| HeadingFontWeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table>                                                                                                                                                                                                                                       |
| HeadingSize       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                                                                                                                                                                                                                                                       |
| Height            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height - 190<td style="background-color:#ffcccc; width:50%;">500</td></tr></table>                                                                                                                                                                                                                                                     |
| InputFill         | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                |
| InvertedColor     | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                                |
| LinkColor         | <table border="0"><tr><td>RGBA(0, 134, 208, 1)</td></tr><tr><td style="background-color:#0086D0"></td></tr></table>                                                                                                                                                                                                                                                                                                  |
| PrimaryColor1     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(73, 130, 5, 1)</td></tr><tr><td style="background-color:#498205"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>       |
| PrimaryColor2     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ColorFade(RGBA(73, 130, 5, 1), -30%)<td style="background-color:#ffcccc; width:50%;">RGBA(0, 18, 107, 1)</td></tr></table>                                                                                                                                                                                                                    |
| PrimaryColor3     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ColorFade(RGBA(73, 130, 5, 1), -50%)<td style="background-color:#ffcccc; width:50%;">RGBA(186, 202, 226, 1)</td></tr></table>                                                                                                                                                                                                                 |
| SelectedColor     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>           |
| SelectedFill      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ColorFade(RGBA(54, 176, 75, 1), 20%)<td style="background-color:#ffcccc; width:50%;">RGBA(56, 96, 178, .2)</td></tr></table>                                                                                                                                                                                                                  |
| Size              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">11<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                                                                                                                                                                                                                                                       |
| Width             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width - 20<td style="background-color:#ffcccc; width:50%;">800</td></tr></table>                                                                                                                                                                                                                                                       |
| X                 | 10                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Y                 | 120                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ZIndex            | 2                                                                                                                                                                                                                                                                                                                                                                                                                    |

### Color Properties

| Property      | Value                                                                                                                                                                                                                                                                                                                                                                                                              |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor   | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(153, 153, 153, 0.8)</td></tr><tr><td style="background-color:#999999"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table> |
| Color         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>         |
| DisabledColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                              |
| Fill          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>      |
| HoverColor    | <table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                    |
| HoverFill     | ColorFade(RGBA(54, 176, 75, 1), 60%)                                                                                                                                                                                                                                                                                                                                                                               |

### Child & Parent Controls

| Property       | Value                                          |
| -------------- | ---------------------------------------------- |
| Child Control  | Project ID\_Column1                            |
| Child Control  | ProjectName\_Column1                           |
| Child Control  | Aggregation ID\_Column1                        |
| Child Control  | Mercuria Cycle\_Column1                        |
| Child Control  | ProjectCounterpart\_Columna1                   |
| Child Control  | Created\_Columna1                              |
| Child Control  | No\_x002e\_PHINA\_Columna1                     |
| Child Control  | ImplementationPartner\_Columna1                |
| Child Control  | State\_Column1                                 |
| Child Control  | Municipality\_x0028\_ies\_x0029\_\_Columna1    |
| Child Control  | LandTenureType\_Columna1                       |
| Child Control  | ProjectoType\_Columna1                         |
| Child Control  | Program\_Columna1                              |
| Child Control  | TransactionType\_Columna1                      |
| Child Control  | OriginationLead\_Columna1                      |
| Child Control  | OriginationPromoter\_Columna1                  |
| Child Control  | OriginationStatus\_Columna1                    |
| Child Control  | ApprovedBuyer\_Columna1                        |
| Child Control  | ProjectApprovalDate\_Columna1                  |
| Child Control  | ERPAApprovalDate\_Columna1                     |
| Child Control  | ProspectPriority\_Columna1                     |
| Child Control  | ProjectAlive\_x003f\_\_Columna1                |
| Child Control  | Descripcion\_Columna1                          |
| Child Control  | UnderlyingActivities\_Columna1                 |
| Child Control  | Additionality\_Columna1                        |
| Child Control  | LicensesPermits\_Columna1                      |
| Child Control  | DevelopmentLead\_Columna1                      |
| Child Control  | DevelopmentStatus\_Columna1                    |
| Child Control  | Registry\_Columna1                             |
| Child Control  | RegistrationRoute\_Columna1                    |
| Child Control  | Methodology\_Columna1                          |
| Child Control  | CreditType\_Columna1                           |
| Child Control  | EstimatedUpfrontCostUSD\_Column1               |
| Child Control  | Confidence\_x0020\_of\_x0020\_Upfron\_Columna1 |
| Child Control  | OMCostUSD\_Column1                             |
| Child Control  | CBACalculatorVersion\_Columna1                 |
| Child Control  | CBAFile\_x0028\_Reference\_x0029\_\_Columna1   |
| Child Control  | ProjectAreaha\_Column1                         |
| Child Control  | ActivityAreahaN\_Column1                       |
| Child Control  | ProjectCondition\_Columna1                     |
| Child Control  | ApprovedbyCounterpartProjectStar\_Columna1     |
| Child Control  | Expected2ndCreditingPeriodStartD\_Columna1     |
| Child Control  | DaysofAccreditation1stCreditingP\_Columna1     |
| Child Control  | ERsCalculatorVersion\_Columna1                 |
| Child Control  | MercuriaDDstatus\_Columna1                     |
| Child Control  | DDPacktoMESubmiDDPacktoMESubmiss\_Columna1     |
| Child Control  | SafeguardsLead\_Columna1                       |
| Child Control  | StatusSafeguards\_Columna1                     |
| Child Control  | LastPPTtoProjectCounterpart\_Columna1          |
| Child Control  | Safeguards\_x002f\_noharmapproach\_Columna1    |
| Child Control  | Social\_x002f\_Communitynoharm\_Columna1       |
| Child Control  | SDGclaims\_Columna1                            |
| Child Control  | Shareholdersengagement\_Columna1               |
| Child Control  | Press\_x002d\_negative\_Columna1               |
| Child Control  | Biodiversity\_Columna1                         |
| Child Control  | Humanrights\_Columna1                          |
| Child Control  | Indigenouspeoples\_x002f\_cultural\_Columna1   |
| Child Control  | HS\_Columna1                                   |
| Child Control  | NegativeEHS\_Columna1                          |
| Child Control  | LegalLead\_Columna1                            |
| Child Control  | LegalDDStatus\_Columna1                        |
| Child Control  | LoISignedDate\_Columna1                        |
| Child Control  | MEKYCstatus\_Columna1                          |
| Child Control  | CBRequestedtoRANDate\_Columna1                 |
| Child Control  | CBCompleted\_x003f\_\_Columna1                 |
| Child Control  | ERPASignedDate\_Columna1                       |
| Child Control  | Buyer\_Columna1                                |
| Child Control  | ProjectAggregator\_Columna1                    |
| Child Control  | ProjectDeveloper\_Column1                      |
| Child Control  | ProjectCoordinator\_Column1                    |
| Child Control  | ProjectCoordinatorTerm\_Column1                |
| Child Control  | SpecificConditionsPrescendent\_Column1         |
| Child Control  | KYCtoMESubmissionDate\_Column1                 |
| Child Control  | MRVLead\_Column1                               |
| Child Control  | Permanence\_Column1                            |
| Child Control  | Leakeage\_Column1                              |
| Child Control  | ReversalRisk\_x0028\_removals\_x002\_Column1   |
| Child Control  | MRVRequirements\_Column1                       |
| Child Control  | SampleSize\_Column1                            |
| Child Control  | BLInventoryStartDate\_Column1                  |
| Child Control  | BLInventoryEndDate\_Column1                    |
| Child Control  | MRVStatus\_Column1                             |
| Child Control  | TotalCERT10YRStCO2\_Column1                    |
| Child Control  | CAROnsiteVerificationn\_Column1                |
| Child Control  | CCBSOnisiteVerificationn\_Column1              |
| Child Control  | MonitoringBaselinen\_Column1                   |
| Child Control  | OnesiteImplementationn\_Column1                |
| Child Control  | Originatonn\_Column1                           |
| Child Control  | PDDDevelopmentn\_Column1                       |
| Child Control  | VerificationSupportn\_Column1                  |
| Child Control  | Contingencyn\_Column1                          |
| Child Control  | Totaln\_Column1                                |
| Child Control  | ANNUALOMCTSYEAR2021\_Column1                   |
| Child Control  | ANNUALOMCTSYEAR2022\_Column1                   |
| Child Control  | ANNUALOMCTSYEAR2023\_Column1                   |
| Child Control  | ANNUALOMCTSYEAR2024\_Column1                   |
| Child Control  | ANNUALOMCTSYEAR2025\_Column1                   |
| Child Control  | ANNUALOMCTSYEAR2026\_Column1                   |
| Child Control  | ANNUALOMCTSYEAR2027\_Column1                   |
| Child Control  | ANNUALOMCTSYEAR2028\_Column1                   |
| Child Control  | ANNUALOMCTSYEAR2029\_Column1                   |
| Child Control  | ANNUALOMCTSYEAR2030\_Column1                   |
| Child Control  | ANNUALOMCTSYEAR2031\_Column1                   |
| Child Control  | AOMCDYEAR2021\_Column1                         |
| Child Control  | AOMCDYEAR2022\_Column1                         |
| Child Control  | AOMCDYEAR2023\_Column1                         |
| Child Control  | AOMCDYEAR2024\_Column1                         |
| Child Control  | AOMCDYEAR2025\_Column1                         |
| Child Control  | AOMCDYEAR2026\_Column1                         |
| Child Control  | AOMCDYEAR2027\_Column1                         |
| Child Control  | AOMCDYEAR2028\_Column1                         |
| Child Control  | AOMCDYEAR2029\_Column1                         |
| Child Control  | AOMCDYEAR2030\_Column1                         |
| Child Control  | AOMCDYEAR2031\_Column1                         |
| Child Control  | UCDYEAR2021\_Column1                           |
| Child Control  | UCDYEAR2022\_Column1                           |
| Child Control  | UCDYEAR2023\_Column1                           |
| Child Control  | UCDYEAR2024\_Column1                           |
| Child Control  | UCDYEAR2025\_Column1                           |
| Child Control  | UCDYEAR2026\_Column1                           |
| Child Control  | UCDYEAR2027\_Column1                           |
| Child Control  | UCDYEAR2028\_Column1                           |
| Child Control  | UCDYEAR2029\_Column1                           |
| Child Control  | UCDYEAR2030\_Column1                           |
| Child Control  | UCDYEAR2031\_Column1                           |
| Child Control  | CRTs2021\_Column1                              |
| Child Control  | CRTs2022\_Column1                              |
| Child Control  | CRTs2023\_Column1                              |
| Child Control  | CRTs2024\_Column1                              |
| Child Control  | CRTs2025\_Column1                              |
| Child Control  | CRTs2026\_Column1                              |
| Child Control  | CRTs2027\_Column1                              |
| Child Control  | CRTs2028\_Column1                              |
| Child Control  | CRTs2029\_Column1                              |
| Child Control  | CRTs2030\_Column1                              |
| Child Control  | CRTs2031\_Column1                              |
| Child Control  | CRTs2032\_Column1                              |
| Child Control  | CRTs2033\_Column1                              |
| Child Control  | CRTs2034\_Column1                              |
| Child Control  | CRTs2035\_Column1                              |
| Child Control  | CRTs2036\_Column1                              |
| Child Control  | CRTs2037\_Column1                              |
| Child Control  | CRTs2038\_Column1                              |
| Child Control  | CRTs2039\_Column1                              |
| Child Control  | CRTs2040\_Column1                              |
| Child Control  | CRTs2041\_Column1                              |
| Child Control  | CRTs2042\_Column1                              |
| Child Control  | CRTs2043\_Column1                              |
| Child Control  | CRTs2044\_Column1                              |
| Child Control  | CRTs2045\_Column1                              |
| Child Control  | CRTs2046\_Column1                              |
| Child Control  | CRTs2047\_Column1                              |
| Child Control  | CRTs2048\_Column1                              |
| Child Control  | CRTs2049\_Column1                              |
| Child Control  | CRTs2050\_Column1                              |
| Parent Control | Home                                           |

## DaysofAccreditation1stCreditingP\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                                           |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Accreditation Days 1st Period"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"DaysofAccreditation1stCreditingP"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                       |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">42<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Days of Accreditation 1st Crediting Period'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 387                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## DDPacktoMESubmiDDPacktoMESubmiss\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                              |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"DD Pack to ME Submission Date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"DDPacktoMESubmiDDPacktoMESubmiss"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">45<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                       |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'DD Pack to ME Submission Date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 390                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Descripcion\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Descripcion"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Descripcion"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Descripcion<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 367                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## DevelopmentLead\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                 |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Development Lead"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"DevelopmentLead"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">26<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Development Lead'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 371                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## DevelopmentStatus\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Development Status"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"DevelopmentStatus"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">27<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Development Status'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 372                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ERPAApprovalDate\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ERPA Approval Date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ERPAApprovalDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">19<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ERPA Approval Date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 364                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ERPASignedDate\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                 |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ERPA Signed Date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ERPASignedDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">65<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ERPA Signed Date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 410                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ERsCalculatorVersion\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                       |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ERs Calculator Version"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ERsCalculatorVersion"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">43<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ERs Calculator Version'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 388                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## EstimatedUpfrontCostUSD\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                           |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Estimated Up front Cost USD"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"EstimatedUpfrontCostUSD"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">32<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Estimated Upfront Cost USD'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 535                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Expected2ndCreditingPeriodStartD\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                                         |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Expected 2nd Crediting Period Start"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Expected2ndCreditingPeriodStartD"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">41<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Expected 2nd Crediting Period Start Date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 386                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Filter

| Property                            | Value          |
| ----------------------------------- | -------------- |
| ![dropdown](resources/dropdown.png) | Type: dropdown |

### Data

| Property | Value                                                                                                                                                             |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Items    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">colFilter<td style="background-color:#ffcccc; width:50%;">DropDownSample</td></tr></table> |

### Design

| Property                  | Value                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle               | BorderStyle.Solid                                                                                                                                                                                                                                                                                                                                                                                                                  |
| BorderThickness           | 2                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ChevronBackground         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>                  |
| ChevronDisabledBackground | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>                |
| ChevronDisabledFill       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table>                |
| ChevronFill               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(33, 33, 33, 1)</td></tr><tr><td style="background-color:#212121"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table>                   |
| ChevronHoverBackground    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(212, 212, 212, 1)</td></tr><tr><td style="background-color:#D4D4D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(RGBA(56, 96, 178, 1), -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| ChevronHoverFill          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(33, 33, 33, 1)</td></tr><tr><td style="background-color:#212121"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table>                   |
| DisplayMode               | DisplayMode.Edit                                                                                                                                                                                                                                                                                                                                                                                                                   |
| FocusedBorderThickness    | 4                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Font                      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                                                                                                                                                                                                                                                          |
| FontWeight                | FontWeight.Normal                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Height                    | 40                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Italic                    | false                                                                                                                                                                                                                                                                                                                                                                                                                              |
| PaddingBottom             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                                                                                                                                                                                                                                      |
| PaddingLeft               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                                                                                                                                                                                                                                     |
| PaddingRight              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                                                                                                                                                                                                                                      |
| PaddingTop                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;">10</td></tr></table>                                                                                                                                                                                                                                                                                      |
| Size                      | 13                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Strikethrough             | false                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Underline                 | false                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Width                     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">350<td style="background-color:#ffcccc; width:50%;">328</td></tr></table>                                                                                                                                                                                                                                                                                   |
| X                         | 0                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Y                         | 0                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ZIndex                    | 1                                                                                                                                                                                                                                                                                                                                                                                                                                  |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>    |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>       |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| Fill                | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | ColorFade(RGBA(73, 130, 5, 1), \-30%)                                                                                                                                                                                                                                                                                                                                                                               |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(212, 212, 212, 1)</td></tr><tr><td style="background-color:#D4D4D4"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(186, 202, 226, 1)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table></td></tr></table> |
| PressedBorderColor  | ColorFade(RGBA(73, 130, 5, 1), \-30%)                                                                                                                                                                                                                                                                                                                                                                               |
| PressedColor        | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(73, 130, 5, 1)</td></tr><tr><td style="background-color:#498205"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>       |
| SelectionColor      | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| SelectionFill       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(73, 130, 5, 1)</td></tr><tr><td style="background-color:#498205"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>      |

### Child & Parent Controls

| Property       | Value     |
| -------------- | --------- |
| Parent Control | FilterBar |

## FilterBar

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">60<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.End<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| PaddingTop           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 2                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Child Control  | Filter          |
| Parent Control | SearchFilterBar |

## HeaderTitle

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 1                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Child Control  | HeaderTitleLogo |
| Child Control  | HeaderTitleName |
| Parent Control | ContainerHeader |

## HeaderTitleLogo

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Data

| Property | Value                                                                                                                                                             |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">'logo-light'<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                            |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">2</td></tr></table>                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                             |
| ImagePosition          | ImagePosition.Fit                                                                                                                                                           |
| ImageRotation          | ImageRotation.None                                                                                                                                                          |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">6<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| PaddingLeft            | 0                                                                                                                                                                           |
| PaddingRight           | 0                                                                                                                                                                           |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">6<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| RadiusBottomLeft       | 0                                                                                                                                                                           |
| RadiusBottomRight      | 0                                                                                                                                                                           |
| RadiusTopLeft          | 0                                                                                                                                                                           |
| RadiusTopRight         | 0                                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">53<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                             |
| X                      | 0                                                                                                                                                                           |
| Y                      | 718                                                                                                                                                                         |
| ZIndex                 | 1                                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>               |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>            |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table>            |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                          |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                         |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>         |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>        |

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | HeaderTitle |

## HeaderTitleName

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                            |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                         |
| Role     | TextRole.Default                                                                                                                                                 |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Canopia Carbon"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                                                     |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>    |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                               |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                   |
| Font                   | Font.'Open Sans'                                                                                                                                                               |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                 |
| Italic                 | false                                                                                                                                                                          |
| LineHeight             | 1.2                                                                                                                                                                            |
| Overflow               | Overflow.Hidden                                                                                                                                                                |
| PaddingBottom          | 5                                                                                                                                                                              |
| PaddingLeft            | 5                                                                                                                                                                              |
| PaddingRight           | 5                                                                                                                                                                              |
| PaddingTop             | 5                                                                                                                                                                              |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">14<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                 |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">250<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                               |
| X                      | 0                                                                                                                                                                              |
| Y                      | 718                                                                                                                                                                            |
| ZIndex                 | 2                                                                                                                                                                              |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>    |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                         |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                              |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                              |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                     |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                              |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                     |

### Child & Parent Controls

| Property       | Value       |
| -------------- | ----------- |
| Parent Control | HeaderTitle |

## HeaderUser

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">60<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.End<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 4                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Child Control  | HeaderUserName  |
| Child Control  | HeaderUserImage |
| Parent Control | ContainerHeader |

## HeaderUserImage

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![image](resources/image.png) | Type: image |

### Data

| Property | Value                                                                                                                                                                                         |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Image    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Office365Users.UserPhotoV2(User().Email)<td style="background-color:#ffcccc; width:50%;">SampleImage</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                            |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">2</td></tr></table>                                |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">45<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                             |
| ImagePosition          | ImagePosition.Fit                                                                                                                                                           |
| ImageRotation          | ImageRotation.None                                                                                                                                                          |
| PaddingBottom          | 0                                                                                                                                                                           |
| PaddingLeft            | 0                                                                                                                                                                           |
| PaddingRight           | 0                                                                                                                                                                           |
| PaddingTop             | 0                                                                                                                                                                           |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                              |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                              |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                              |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                              |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">45<td style="background-color:#ffcccc; width:50%;">100</td></tr></table>                             |
| X                      | 1315                                                                                                                                                                        |
| Y                      | 723                                                                                                                                                                         |
| ZIndex                 | 2                                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>               |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>            |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table></td></tr></table>            |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                          |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                         |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>  |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, 20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>         |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.BorderColor, -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>ColorFade(Self.Fill, -20%)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>        |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | HeaderUser |

## HeaderUserName

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                           |
| -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                        |
| Role     | TextRole.Default                                                                                                                                                |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">User().FullName<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                         |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Right<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>               |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table>   |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                  |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                              |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                  |
| Font                   | Font.'Open Sans'                                                                                                                                                              |
| FontWeight             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Lighter<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table> |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                                |
| Italic                 | false                                                                                                                                                                         |
| LineHeight             | 1.2                                                                                                                                                                           |
| Overflow               | Overflow.Hidden                                                                                                                                                               |
| PaddingBottom          | 5                                                                                                                                                                             |
| PaddingLeft            | 5                                                                                                                                                                             |
| PaddingRight           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>                                 |
| PaddingTop             | 5                                                                                                                                                                             |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                |
| Strikethrough          | false                                                                                                                                                                         |
| Underline              | false                                                                                                                                                                         |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                          |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">414<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                              |
| X                      | 890                                                                                                                                                                           |
| Y                      | 718                                                                                                                                                                           |
| ZIndex                 | 1                                                                                                                                                                             |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>    |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                         |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| Fill                | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                              |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                              |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                     |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                              |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                     |

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | HeaderUser |

## HS\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"H&S"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"HS"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">57<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'H&S'<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 402                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Humanrights\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                             |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Human Rights"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Humanrights"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">55<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Human rights'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 400                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Icon1

| Property                    | Value      |
| --------------------------- | ---------- |
| ![icon](resources/icon.png) | Type: icon |

### Behavior

| Property | Value                                                                                                                                                          |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Refresh(Portafolio);<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property        | Value                                                                                                                                                       |
| --------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AccessibleLabel | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Refrescar datos"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Tooltip         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Refrescar datos"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property               | Value                                                                                                                                                       |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| DisplayMode            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">40<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Icon                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Icon.Sync<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| PaddingBottom          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">6<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| PaddingTop             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">120<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| X                      | 0                                                                                                                                                           |
| Y                      | 0                                                                                                                                                           |
| ZIndex                 | 2                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 148, 110, 1)</td></tr><tr><td style="background-color:#00946E"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>   |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| DisabledColor       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(220, 220, 220, 1)</td></tr><tr><td style="background-color:#DCDCDC"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| DisabledFill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                           |
| HoverBorderColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| HoverColor          | ColorFade(RGBA(0, 148, 110, 1), \-30%)                                                                                                                                                                                                                                                                                                     |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |
| PressedColor        | ColorFade(RGBA(73, 130, 5, 1), \-30%)                                                                                                                                                                                                                                                                                                      |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>       |

### Child & Parent Controls

| Property       | Value     |
| -------------- | --------- |
| Parent Control | SearchBar |

## ImplementationPartner\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                       |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Implementation Partner"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ImplementationPartner"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">7<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Implementation Partner'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">250<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 353                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Indigenouspeoples\_x002f\_cultural\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                                       |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Indigenous peoples / Cultural heritage"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Indigenouspeoples_x002f_cultural"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">56<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Indigenous peoples / cultural heritage'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 401                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## InpSearch

| Property                    | Value      |
| --------------------------- | ---------- |
| ![text](resources/text.png) | Type: text |

### Data

| Property    | Value                                                                                                                                                    |
| ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Default     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">""<td style="background-color:#ffcccc; width:50%;">"Text input"</td></tr></table> |
| DelayOutput | false                                                                                                                                                    |
| HintText    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Buscar"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |

### Design

| Property               | Value                                                                                                                                            |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | Align.Left                                                                                                                                       |
| BorderStyle            | BorderStyle.Solid                                                                                                                                |
| BorderThickness        | 2                                                                                                                                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                 |
| FocusedBorderThickness | 4                                                                                                                                                |
| Font                   | Font.'Open Sans'                                                                                                                                 |
| FontWeight             | FontWeight.Normal                                                                                                                                |
| Format                 | TextFormat.Text                                                                                                                                  |
| Height                 | 40                                                                                                                                               |
| Italic                 | false                                                                                                                                            |
| Mode                   | TextMode.SingleLine                                                                                                                              |
| PaddingLeft            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">7<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| RadiusBottomLeft       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>     |
| RadiusBottomRight      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>     |
| RadiusTopLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>     |
| RadiusTopRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">5</td></tr></table>     |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">11<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>   |
| Strikethrough          | false                                                                                                                                            |
| Underline              | false                                                                                                                                            |
| VirtualKeyboardMode    | VirtualKeyboardMode.Auto                                                                                                                         |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">250<td style="background-color:#ffcccc; width:50%;">320</td></tr></table> |
| X                      | 0                                                                                                                                                |
| Y                      | 0                                                                                                                                                |
| ZIndex                 | 1                                                                                                                                                |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>    |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table></td></tr></table>       |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| DisabledFill        | <table border="0"><tr><td>RGBA(244, 244, 244, 1)</td></tr><tr><td style="background-color:#F4F4F4"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| Fill                | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverBorderColor    | ColorFade(RGBA(73, 130, 5, 1), \-30%)                                                                                                                                                                                                                                                                                                                                                                               |
| HoverColor          | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>          |
| HoverFill           | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(186, 202, 226, 1)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table></td></tr></table> |
| PressedBorderColor  | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(73, 130, 5, 1)</td></tr><tr><td style="background-color:#498205"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.HoverBorderColor</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>     |
| PressedColor        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Color</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>                |
| PressedFill         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>Self.Fill</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>              |

### Child & Parent Controls

| Property       | Value     |
| -------------- | --------- |
| Parent Control | SearchBar |

## KYCtoMESubmissionDate\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"KYC to ME Submission Date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"KYCtoMESubmissionDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">72<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'KYC to ME Submission Date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 417                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## LabelMantenimiento

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                                                                                                                                                                                    |
| -------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Live     | Live.Off                                                                                                                                                                                                                                                                                                                 |
| Role     | TextRole.Default                                                                                                                                                                                                                                                                                                         |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Estamos trabajando para ti, disculpa el inconveniente. Intenta de nuevo mas tarde. AREA DE SISTEMAS Cualquier inquietud contactanos al correo marcos@canopiacarbon.com"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                       |
| ---------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>            |
| BorderStyle            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.None<td style="background-color:#ffcccc; width:50%;">BorderStyle.Solid</td></tr></table> |
| BorderThickness        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| DisplayMode            | DisplayMode.Edit                                                                                                                                                            |
| FocusedBorderThickness | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;">0</td></tr></table>                                |
| Font                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>   |
| FontWeight             | FontWeight.Normal                                                                                                                                                           |
| Height                 | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;">40</td></tr></table>                   |
| Italic                 | false                                                                                                                                                                       |
| LineHeight             | 1.2                                                                                                                                                                         |
| Overflow               | Overflow.Hidden                                                                                                                                                             |
| PaddingBottom          | 5                                                                                                                                                                           |
| PaddingLeft            | 5                                                                                                                                                                           |
| PaddingRight           | 5                                                                                                                                                                           |
| PaddingTop             | 5                                                                                                                                                                           |
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">28<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                              |
| Strikethrough          | false                                                                                                                                                                       |
| Underline              | false                                                                                                                                                                       |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                        |
| Visible                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                   |
| X                      | 0                                                                                                                                                                           |
| Y                      | 0                                                                                                                                                                           |
| ZIndex                 | 3                                                                                                                                                                           |

### Color Properties

| Property            | Value                                                                                                                                                                                                                                                                                                                                                                                                         |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>    |
| Color               | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 148, 110, 1)</td></tr><tr><td style="background-color:#00946E"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>   |
| DisabledBorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 56, 56, 1)</td></tr><tr><td style="background-color:#383838"></td></tr></table></td></tr></table>    |
| DisabledColor       | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                         |
| DisabledFill        | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                               |
| Fill                | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table> |
| FocusedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                              |
| HoverBorderColor    | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                              |
| HoverColor          | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                    |
| HoverFill           | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                     |
| PressedBorderColor  | Self.BorderColor                                                                                                                                                                                                                                                                                                                                                                                              |
| PressedColor        | Self.Color                                                                                                                                                                                                                                                                                                                                                                                                    |
| PressedFill         | Self.Fill                                                                                                                                                                                                                                                                                                                                                                                                     |

### Child & Parent Controls

| Property       | Value |
| -------------- | ----- |
| Parent Control | Home  |

## LandTenureType\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                 |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Land Tenure Type"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"LandTenureType"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Land Tenure Type'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 355                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## LastPPTtoProjectCounterpart\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Behavior

| Property | Value                                                                                                                                                                                                       |
| -------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| OnSelect | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Launch(DataPortafolio.Selected.'Last PPT to Project Counterpart')<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Data

| Property         | Value                                                                                                                                                                                |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Last PPT to Counterpart"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"LastPPTtoProjectCounterpart"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| IsHyperlink      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                       |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">48<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                         |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Last PPT to Project Counterpart'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 393                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Leakeage\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Leakeage"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Leakeage"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">75<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Estimated Leakeage'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 420                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## LegalDDStatus\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Legal DD Status"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"LegalDDStatus"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">60<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Legal DD Status'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 405                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## LegalLead\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                           |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Legal Lead"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"LegalLead"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">59<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Legal Lead'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 404                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## LicensesPermits\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Licenses & Permits"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"LicensesPermits"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">25<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Licenses & Permits'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 370                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## LoISignedDate\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"LoI Signed Date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"LoISignedDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">61<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'LoI Signed Date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 406                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## MEKYCstatus\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                              |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ME KYC Status"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"MEKYCstatus"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">62<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'ME KYC status'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 407                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Mercuria Cycle\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                               |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Mercuria Cycle"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"MercuriaCycle"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Mercuria Cycle'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">131<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 655                                                                                                                                                        |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 7                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## MercuriaDDstatus\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Mercuria DD status"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"MercuriaDDstatus"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">44<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Mercuria DD status'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 389                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Methodology\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Methodology"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Methodology"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Methodology<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 375                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## MonitoringBaselinen\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Monitoring Baseline"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"MonitoringBaselinen"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">188<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Monitoring Baseline'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 6 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 539                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## MRVLead\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"MRV Lead"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"MRVLead"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">73<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'MRV Lead'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 418                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## MRVRequirements\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                           |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"MRV Requirements"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"MRVRequirements"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">77<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Estimated MRV Requirements'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 422                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## MRVStatus\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                           |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"MRV Status"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"MRVStatus"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">81<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'MRV Status'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 426                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Municipality\_x0028\_ies\_x0029\_\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Municipality(ies)"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Municipality_x0028_ies_x0029_"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">9<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.' Municipality(ies)'<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 354                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## NavBar

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                       |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">60<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Center<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.SpaceBetween<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| PaddingRight         | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">30<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Width<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| X                    | 0                                                                                                                                                                           |
| Y                    | Parent.Y + Parent.Height +60                                                                                                                                                |
| ZIndex               | 1                                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                    |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>     |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 148, 110, 1)</td></tr><tr><td style="background-color:#00946E"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Child Control  | Container4      |
| Child Control  | Container5      |
| Parent Control | ContainerFooter |

## NegativeEHS\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                             |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Negative EHS"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"NegativeEHS"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">58<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Negative EHS'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 403                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## No\_x002e\_PHINA\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                          |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"No PHINA"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"No_x002e_PHINA"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">6<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'No. PHINA'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 352                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## OMCostUSD\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                             |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"O&M Cost USD"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"OMCostUSD"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">34<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'O&M Cost USD'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 536                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## OnesiteImplementationn\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                      |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Onsite Implementation"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"OnesiteImplementationn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">189<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Onsite Implementation'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 6 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 540                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## OriginationLead\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                 |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Origination Lead"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"OriginationLead"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">14<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Origination Lead'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                               |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false) <td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                       |
| X            | 0                                                                                                                                                                                   |
| Y            | 0                                                                                                                                                                                   |
| ZIndex       | 359                                                                                                                                                                                 |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## OriginationPromoter\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Origination Promoter"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"OriginationPromoter"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">15<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Origination Promoter'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 360                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## OriginationStatus\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Origination Status"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"OriginationStatus"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">16<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Origination Status'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 361                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Originatonn\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Originaton"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Originatonn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">190<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Originaton<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 6 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 541                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## PDDDevelopmentn\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"PDD Development"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"PDDDevelopmentn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">191<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'PDD Development'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 6 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 542                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Permanence\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Permanence"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Permanence"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">74<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Estimated Permanence'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 419                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Press\_x002d\_negative\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                 |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Press - negative"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Press_x002d_negative"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">53<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Press - negative'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 398                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Program\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                      |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Program"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Program"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Program<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 357                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Project ID\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                           |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AutoWidth        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Project ID"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectID"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project ID'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">222<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 22                                                                                                                                                         |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 8                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectAggregator\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Project Aggregator"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectAggregator"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">67<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Aggregator'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 412                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectAlive\_x003f\_\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                               |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Project Alive"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectAlive_x003f_"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">21<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Alive?'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 366                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectApprovalDate\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                      |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Project Approval Date"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectApprovalDate"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">18<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Approval Date'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 363                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectAreaha\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Project Area (ha)"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectAreaha"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">37<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Area ha'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 502                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectCondition\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                  |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Project Condition"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectCondition"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">39<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Condition'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 384                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectCoordinator\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Project Coordinator"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectCoordinator"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">69<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Coordinator'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 414                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectCoordinatorTerm\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                         |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Project Coordinator Term"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectCoordinatorTerm"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">70<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                  |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Coordinator Term'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 415                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectCounterpart\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Project Counterpart"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectCounterpart"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5 <td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Counterpart'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 500                                                                                                                                                        |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectDeveloper\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                  |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Project Developer"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectDeveloper"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">68<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Developer'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 413                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectName\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                             |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectName"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectName"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Name'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 157                                                                                                                                                        |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 350                                                                                                                                                        |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProjectoType\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                             |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Projecto Type"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProjectoType"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">11<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Project Type'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 356                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ProspectPriority\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                  |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Prospect Priority"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ProspectPriority"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">20<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Prospect Priority'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 365                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## RegistrationRoute\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"RegistrationRoute"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"RegistrationRoute"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">29<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Registration Route'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 374                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Registry\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                       |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Registry"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Registry"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">28<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Registry<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 373                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## ReversalRisk\_x0028\_removals\_x002\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                                   |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Reversal Risk (removals)"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"ReversalRisk_x0028_removals_x002"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">76<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                            |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Estimated Reversal Risk (removals)'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 421                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Safeguards\_x002f\_noharmapproach\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                            |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Safeguards / No harm approach"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Safeguards_x002f_noharmapproach"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">49<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Safeguards/no harm approach'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 394                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## SafeguardsLead\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Safeguards Lead"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"SafeguardsLead"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">46<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Safeguards Lead'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 391                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## SampleSize\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                      |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Sample Size"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"SampleSize"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                     |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">78<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Estimated Sample Size'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 423                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## SDGclaims\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                           |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"SDGclaims"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"SDGclaims"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">51<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'SDG claims'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 396                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## SearchBar

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">60<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| PaddingLeft          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| PaddingTop           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">350<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 1                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value           |
| -------------- | --------------- |
| Child Control  | InpSearch       |
| Child Control  | Icon1           |
| Parent Control | SearchFilterBar |

## SearchFilterBar

| Property                                                                      | Value                               |
| ----------------------------------------------------------------------------- | ----------------------------------- |
| ![horizontalAutoLayoutContainer](resources/horizontalAutoLayoutContainer.png) | Type: horizontalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                       |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                              |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">200<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.SpaceBetween<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| RadiusBottomLeft     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusBottomRight    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusTopLeft        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| RadiusTopRight       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| X                    | 0                                                                                                                                                                           |
| Y                    | 0                                                                                                                                                                           |
| ZIndex               | 2                                                                                                                                                                           |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value             |
| -------------- | ----------------- |
| Child Control  | SearchBar         |
| Child Control  | FilterBar         |
| Parent Control | ContainerInferior |

## Shareholdersengagement\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                        |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Shareholders Engagement"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Shareholdersengagement"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                    |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">52<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Shareholders engagement'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 397                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Social\_x002f\_Communitynoharm\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Social / Community no harm"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Social_x002f_Communitynoharm"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">50<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                   |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Social/ Community no harm'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 395                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## SpecificConditionsPrescendent\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                                |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Specific Conditions Prescendent"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"SpecificConditionsPrescendent"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">71<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                         |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Specific Conditions Prescendent'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 4 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 416                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## State\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"State"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"State"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">8<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.State<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 1186                                                                                                                                                       |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 351                                                                                                                                                        |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## StatusSafeguards\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                  |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Status Safeguards"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"StatusSafeguards"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">47<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Status Safeguards'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 3 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 392                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## TotalCERT10YRStCO2\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                       |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Total CERT 10 YRS tCO2"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"TotalCERT10YRStCO2"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">155<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Total CERT 10 YRS tCO2'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 5 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 504                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## Totaln\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Total"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Totaln"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">194<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.Total<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 6 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 545                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## TransactionType\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                 |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Transaction Type"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"TransactionType"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">13<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Transaction Type'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 1 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 358                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2021\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2022"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2021"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">217<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2022'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 568                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2022\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2023"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2022"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">218<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2023'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 569                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2023\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2024"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2023"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">219<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2024'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 570                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2024\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2025"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2024"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">220<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2025'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 571                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2025\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2026"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2025"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">221<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2026'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 572                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2026\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2027"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2026"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">222<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2027'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 573                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2027\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2028"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2027"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">223<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2028'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 574                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2028\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2029"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2028"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">224<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2029'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 575                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2029\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2030"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2029"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">225<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2030'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 576                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2030\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2031"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2030"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">226<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2031'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 577                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UCDYEAR2031\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCD 2032"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UCDYEAR2031"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">227<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'UCD 2032'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                             |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 8, true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                     |
| X            | 0                                                                                                                                                                                 |
| Y            | 0                                                                                                                                                                                 |
| ZIndex       | 578                                                                                                                                                                               |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## UnderlyingActivities\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                      |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Underlying Activities"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"UnderlyingActivities"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">23<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                               |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Underlying Activities'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 2 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 368                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |

## VerificationSupportn\_Column1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Verification Support "<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"VerificationSupportn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">192<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                             |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'Verification Support'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                                              |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                            |
| Visible      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">If(Filter.Selected.ID = 6 , true, false)<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                      |
| X            | 0                                                                                                                                                                                  |
| Y            | 0                                                                                                                                                                                  |
| ZIndex       | 543                                                                                                                                                                                |

### Color Properties

### Child & Parent Controls

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | DataPortafolio |
