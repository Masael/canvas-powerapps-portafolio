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

## Inventario\_mrv

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
| Fill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>White</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property      | Value            |
| ------------- | ---------------- |
| Child Control | ScreenContainer1 |
| Child Control | DataTable1       |

## altura\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"altura"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_4"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>       |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"numberColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">5<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.altura<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 8                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## DataTable1

| Property                              | Value           |
| ------------------------------------- | --------------- |
| ![dataTable](resources/dataTable.png) | Type: dataTable |

### Data

| Property | Value                                                                                                                                                    |
| -------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Items    | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">inventario_mrv<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property          | Value                                                                                                                                                                                                                                                                                                                                                                                                            |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle       | BorderStyle.Solid                                                                                                                                                                                                                                                                                                                                                                                                |
| BorderThickness   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">3<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                                                                                                                                                                                                                                                                      |
| DisplayMode       | DisplayMode.Edit                                                                                                                                                                                                                                                                                                                                                                                                 |
| Font              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Open Sans Condensed'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                                                                                                                                                                                                                             |
| FontWeight        | FontWeight.Normal                                                                                                                                                                                                                                                                                                                                                                                                |
| HeadingColor      | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                            |
| HeadingFill       | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(73, 130, 5, 1)</td></tr><tr><td style="background-color:#498205"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>   |
| HeadingFont       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Font.'Segoe UI'<td style="background-color:#ffcccc; width:50%;">Font.'Open Sans'</td></tr></table>                                                                                                                                                                                                                                        |
| HeadingFontWeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">FontWeight.Semibold<td style="background-color:#ffcccc; width:50%;">FontWeight.Normal</td></tr></table>                                                                                                                                                                                                                                   |
| HeadingSize       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                                                                                                                                                                                                                                                   |
| Height            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">546<td style="background-color:#ffcccc; width:50%;">500</td></tr></table>                                                                                                                                                                                                                                                                 |
| InputFill         | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                            |
| InvertedColor     | <table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table>                                                                                                                                                                                                                                                                                            |
| LinkColor         | <table border="0"><tr><td>RGBA(0, 134, 208, 1)</td></tr><tr><td style="background-color:#0086D0"></td></tr></table>                                                                                                                                                                                                                                                                                              |
| PrimaryColor1     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(73, 130, 5, 1)</td></tr><tr><td style="background-color:#498205"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, 1)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table>   |
| PrimaryColor2     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ColorFade(RGBA(73, 130, 5, 1), -30%)<td style="background-color:#ffcccc; width:50%;">RGBA(0, 18, 107, 1)</td></tr></table>                                                                                                                                                                                                                |
| PrimaryColor3     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ColorFade(RGBA(73, 130, 5, 1), -50%)<td style="background-color:#ffcccc; width:50%;">RGBA(186, 202, 226, 1)</td></tr></table>                                                                                                                                                                                                             |
| SelectedColor     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>       |
| SelectedFill      | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(73, 130, 5, .2)</td></tr><tr><td style="background-color:#498205"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(56, 96, 178, .2)</td></tr><tr><td style="background-color:#3860B2"></td></tr></table></td></tr></table> |
| Size              | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">11<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                                                                                                                                                                                                                                                   |
| Width             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1298<td style="background-color:#ffcccc; width:50%;">800</td></tr></table>                                                                                                                                                                                                                                                                |
| X                 | 2                                                                                                                                                                                                                                                                                                                                                                                                                |
| Y                 | 140                                                                                                                                                                                                                                                                                                                                                                                                              |
| ZIndex            | 2                                                                                                                                                                                                                                                                                                                                                                                                                |

### Color Properties

| Property      | Value                                                                                                                                                                                                                                                                                                                                                                                                             |
| ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor   | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 18, 107, 1)</td></tr><tr><td style="background-color:#00126B"></td></tr></table></td></tr></table>        |
| Color         | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(51, 51, 51, 1)</td></tr><tr><td style="background-color:#333333"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>        |
| DisabledColor | <table border="0"><tr><td>RGBA(166, 166, 166, 1)</td></tr><tr><td style="background-color:#A6A6A6"></td></tr></table>                                                                                                                                                                                                                                                                                             |
| Fill          | <table border="0"><tr><td>RGBA(0, 0, 0, 0)</td></tr><tr><td style="background-color:#000000"></td></tr></table>                                                                                                                                                                                                                                                                                                   |
| HoverColor    | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(255, 255, 255, 1)</td></tr><tr><td style="background-color:#FFFFFF"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td></tr></table>     |
| HoverFill     | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(73, 130, 5, 1)</td></tr><tr><td style="background-color:#498205"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td>RGBA(186, 202, 226, .2)</td></tr><tr><td style="background-color:#BACAE2"></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value                      |
| -------------- | -------------------------- |
| Child Control  | id muestreo\_Columna1      |
| Child Control  | numero de arbol\_Columna1  |
| Child Control  | diametro\_Columna1         |
| Child Control  | altura\_Columna1           |
| Child Control  | longitud de copa\_Columna1 |
| Child Control  | vigor\_Columna1            |
| Child Control  | referencia a\_Columna1     |
| Child Control  | referencia b\_Columna1     |
| Child Control  | defecto bajo\_Columna1     |
| Child Control  | defecto medio\_Columna1    |
| Child Control  | defecto superior\_Columna1 |
| Child Control  | especie\_Columna1          |
| Parent Control | Inventario\_mrv            |

## defecto bajo\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                             |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"defecto bajo"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_9"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"numberColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">10<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'defecto bajo'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 13                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## defecto medio\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                              |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"defecto medio"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_10"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"numberColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">11<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'defecto medio'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 14                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## defecto superior\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                 |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"defecto superior"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_11"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"numberColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">12<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'defecto superior'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 15                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## diametro\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                       |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"diametro"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_3"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">4<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                 |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.diametro<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 7                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## especie\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                      |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"especie"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_2"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>  |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">3<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.especie<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 34                                                                                                                                                         |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 6                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## HeaderContainer1

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
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">75<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                         |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table>     |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Horizontal<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Width                | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">500<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| X                    | 0                                                                                                                                                                    |
| Y                    | 0                                                                                                                                                                    |
| ZIndex               | 2                                                                                                                                                                    |

### Color Properties

| Property    | Value                                                                                                                                                                                                                                                                                                                                    |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderColor | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 0, 0, 1)</td></tr><tr><td style="background-color:#000000"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table>     |
| Fill        | <table border="0"><tr><td style="width:50%; background-color:#ccffcc; color:black;"><table border="0"><tr><td>RGBA(0, 148, 110, 1)</td></tr><tr><td style="background-color:#00946E"></td></tr></table></td><td style="width:50%; background-color:#ffcccc; color:black;"><table border="0"><tr><td></td></tr></table></td></tr></table> |

### Child & Parent Controls

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | HeaderTitle\_6   |
| Parent Control | ScreenContainer1 |

## HeaderTitle\_6

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

| Property       | Value              |
| -------------- | ------------------ |
| Child Control  | HeaderTitleLogo\_6 |
| Child Control  | HeaderTitleName\_6 |
| Child Control  | HeaderTitleName\_7 |
| Parent Control | HeaderContainer1   |

## HeaderTitleLogo\_6

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

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | HeaderTitle\_6 |

## HeaderTitleName\_6

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

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | HeaderTitle\_6 |

## HeaderTitleName\_7

| Property                      | Value       |
| ----------------------------- | ----------- |
| ![label](resources/label.png) | Type: label |

### Data

| Property | Value                                                                                                                                                            |
| -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Live     | Live.Off                                                                                                                                                         |
| Role     | TextRole.Default                                                                                                                                                 |
| Text     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Inventario_mrv"<td style="background-color:#ffcccc; width:50%;">"Text"</td></tr></table> |

### Design

| Property               | Value                                                                                                                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Align                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Align.Center<td style="background-color:#ffcccc; width:50%;">Align.Left</td></tr></table>               |
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
| Size                   | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">22<td style="background-color:#ffcccc; width:50%;">13</td></tr></table>                                 |
| Strikethrough          | false                                                                                                                                                                          |
| Underline              | false                                                                                                                                                                          |
| VerticalAlign          | VerticalAlign.Middle                                                                                                                                                           |
| Width                  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">250<td style="background-color:#ffcccc; width:50%;">150</td></tr></table>                               |
| X                      | 0                                                                                                                                                                              |
| Y                      | 718                                                                                                                                                                            |
| ZIndex                 | 3                                                                                                                                                                              |

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

| Property       | Value          |
| -------------- | -------------- |
| Parent Control | HeaderTitle\_6 |

## id muestreo\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"id muestreo"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"Title"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">1<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'id muestreo'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 4                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## longitud de copa\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                 |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"longitud de copa"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_5"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                   |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"numberColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">6<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                           |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'longitud de copa'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 9                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## numero de arbol\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                                |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"numero de arbol"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_1"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                  |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"numberColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>             |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">2<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'numero de arbol'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 5                                                                                                                                                          |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## referencia a\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                             |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"referencia a"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_7"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">8<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'referencia a'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 11                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## referencia b\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                             |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"referencia b"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_8"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>               |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"textualColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>         |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">9<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.'referencia b'<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 12                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |

## ScreenContainer1

| Property                                                                  | Value                             |
| ------------------------------------------------------------------------- | --------------------------------- |
| ![verticalAutoLayoutContainer](resources/verticalAutoLayoutContainer.png) | Type: verticalAutoLayoutContainer |

### Design

| Property             | Value                                                                                                                                                                |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BorderStyle          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">BorderStyle.Solid<td style="background-color:#ffcccc; width:50%;"></td></tr></table>          |
| ChildTabPriority     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">true<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                       |
| DisplayMode          | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table>           |
| DropShadow           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DropShadow.None<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| Height               | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">768<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                        |
| LayoutAlignItems     | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutAlignItems.Stretch<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutDirection      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutDirection.Vertical<td style="background-color:#ffcccc; width:50%;"></td></tr></table>   |
| LayoutGap            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">0<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                          |
| LayoutJustifyContent | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutJustifyContent.Start<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| LayoutMode           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutMode.Auto<td style="background-color:#ffcccc; width:50%;"></td></tr></table>            |
| LayoutOverflowX      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutOverflowY      | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">LayoutOverflow.Hide<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| LayoutWrap           | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">false<td style="background-color:#ffcccc; width:50%;"></td></tr></table>                      |
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

| Property       | Value            |
| -------------- | ---------------- |
| Child Control  | HeaderContainer1 |
| Parent Control | Inventario\_mrv  |

## vigor\_Columna1

| Property                                          | Value                 |
| ------------------------------------------------- | --------------------- |
| ![dataTableColumn](resources/dataTableColumn.png) | Type: dataTableColumn |

### Data

| Property         | Value                                                                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FieldDisplayName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"vigor"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>        |
| FieldName        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"field_6"<td style="background-color:#ffcccc; width:50%;"></td></tr></table>      |
| FieldVariantName | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">"numberColumn"<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Order            | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">7<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| Text             | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">ThisItem.vigor<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |

### Design

| Property     | Value                                                                                                                                                      |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| DisplayMode  | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">DisplayMode.Edit<td style="background-color:#ffcccc; width:50%;"></td></tr></table> |
| Height       | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| LayoutHeight | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">Parent.Height<td style="background-color:#ffcccc; width:50%;"></td></tr></table>    |
| Width        | <table border="0"><tr><td style="background-color:#ccffcc; width:50%;">100<td style="background-color:#ffcccc; width:50%;"></td></tr></table>              |
| X            | 0                                                                                                                                                          |
| Y            | 0                                                                                                                                                          |
| ZIndex       | 10                                                                                                                                                         |

### Color Properties

### Child & Parent Controls

| Property       | Value      |
| -------------- | ---------- |
| Parent Control | DataTable1 |
