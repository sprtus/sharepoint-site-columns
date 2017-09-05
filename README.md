# Sharepoint Site Columns

### Single line of text
```sh
<SharePoint:TextField FieldName="" runat="server" InputFieldLabel=""/>
```

### Multiple lines of text
```sh
<SharePoint:NoteField FieldName="" runat="server" InputFieldLabel=""/>
```

### Choice (menu to choose from)
```sh
<SharePoint:DropDownChoiceField FieldName="" runat="server" InputFieldLabel=""/>
```

### Number (1, 1.0, 100)
```sh
<SharePoint:NumberField FieldName="" runat="server" InputFieldLabel=""/>
```

### Currency ($, ¥, €)
```sh
<SharePoint:CurrencyField FieldName="" runat="server" InputFieldLabel=""/>
```

### Date and Time
```sh
<SharePoint:DateTimeField FieldName="" runat="server" InputFieldLabel=""/>
```

### Lookup (information already on this site)
```sh
<SharePoint:LookupField FieldName="" runat="server" InputFieldLabel=""/>
```

### Yes/No (check box)
```sh
<SharePoint:BooleanField FieldName="" runat="server" InputFieldLabel=""/>
```

### Person or Group
```sh
<SharePoint:UserField FieldName="" runat="server" InputFieldLabel=""/>
```

### Hyperlink or Picture
```sh
<SharePoint:UrlField FieldName="" runat="server" InputFieldLabel=""/>
```

### Calculated (calculation based on other columns)
```sh
<SharePoint:CalculatedField FieldName="" runat="server" InputFieldLabel=""/>
```

### Task Outcome
```sh
<SharePoint:DropDownChoiceField FieldName="" runat="server" InputFieldLabel=""/>
```

---------------

### Following 5 columns require register tag at top of page layout
```sh
<%@ Register Tagprefix="PublishingWebControls" Namespace="Microsoft.SharePoint.Publishing.WebControls" Assembly="Microsoft.SharePoint.Publishing, Version=16.0.0.0, Culture=neutral, PublicKeyToken=71e9bce111e9429c" %>
```

  ### Full HTML content with formatting and constraints for publishing
  ```sh
  <PublishingWebControls:RichHtmlField FieldName="" runat="server" InputFieldLabel=""/>
  ```

  ### Image with formatting and constraints for publishing
  ```sh
  <PublishingWebControls:RichImageField FieldName="" runat="server" InputFieldLabel=""/>
  ```

  ### Hyperlink with formatting and constraints for publishing
  ```sh
  <PublishingWebControls:RichLinkField FieldName="" runat="server" InputFieldLabel=""/>
  ```

  ### Summary Links data
  ```sh
  <PublishingWebControls:SummaryLinkFieldControl FieldName="" runat="server" InputFieldLabel=""/>
  ```

  ### Rich media data for publishing
  ```sh
  <PublishingWebControls:MediaFieldControl FieldName="" runat="server" InputFieldLabel=""/>
  ```

---------------

### Following column requires register tag at top of page layout
```sh
<%@ Register tagprefix="Taxonomy" namespace="Microsoft.SharePoint.Taxonomy" assembly="Microsoft.SharePoint.Taxonomy, Version=16.0.0.0, Culture=neutral, PublicKeyToken=71e9bce111e9429c" %>
```

  ### Managed Metadata
  ```sh
  <Taxonomy:TaxonomyFieldControl FieldName="" runat="server" InputFieldLabel=""/>
  ```
