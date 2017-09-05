# Sharepoint Site Columns

## Single line of text
<SharePoint:TextField FieldName="" runat="server" InputFieldLabel=""/>

## Multiple lines of text
<SharePoint:NoteField FieldName="" runat="server" InputFieldLabel=""/>

## Choice (menu to choose from)
<SharePoint:DropDownChoiceField FieldName="" runat="server" InputFieldLabel=""/>

## Number (1, 1.0, 100)
<SharePoint:NumberField FieldName="" runat="server" InputFieldLabel=""/>

## Currency ($, ¥, €)
<SharePoint:CurrencyField FieldName="" runat="server" InputFieldLabel=""/>

## Date and Time
<SharePoint:DateTimeField FieldName="" runat="server" InputFieldLabel=""/>

## Lookup (information already on this site)
<SharePoint:LookupField FieldName="" runat="server" InputFieldLabel=""/>

## Yes/No (check box)
<SharePoint:BooleanField FieldName="" runat="server" InputFieldLabel=""/>

## Person or Group
<SharePoint:UserField FieldName="" runat="server" InputFieldLabel=""/>

## Hyperlink or Picture
<SharePoint:UrlField FieldName="" runat="server" InputFieldLabel=""/>

## Calculated (calculation based on other columns)
<SharePoint:CalculatedField FieldName="" runat="server" InputFieldLabel=""/>

## Task Outcome
<SharePoint:DropDownChoiceField FieldName="" runat="server" InputFieldLabel=""/>

---------------

## Following 5 columns require register tag at top of page layout
<%@ Register Tagprefix="PublishingWebControls" Namespace="Microsoft.SharePoint.Publishing.WebControls" Assembly="Microsoft.SharePoint.Publishing, Version=16.0.0.0, Culture=neutral, PublicKeyToken=71e9bce111e9429c" %>

  ## Full HTML content with formatting and constraints for publishing
  <PublishingWebControls:RichHtmlField FieldName="" runat="server" InputFieldLabel=""/>

  ## Image with formatting and constraints for publishing
  <PublishingWebControls:RichImageField FieldName="" runat="server" InputFieldLabel=""/>

  ## Hyperlink with formatting and constraints for publishing
  <PublishingWebControls:RichLinkField FieldName="" runat="server" InputFieldLabel=""/>

  ## Summary Links data
  <PublishingWebControls:SummaryLinkFieldControl FieldName="" runat="server" InputFieldLabel=""/>

  ## Rich media data for publishing
  <PublishingWebControls:MediaFieldControl FieldName="" runat="server" InputFieldLabel=""/>

---------------

## Following column requires register tag at top of page layout
<%@ Register tagprefix="Taxonomy" namespace="Microsoft.SharePoint.Taxonomy" assembly="Microsoft.SharePoint.Taxonomy, Version=16.0.0.0, Culture=neutral, PublicKeyToken=71e9bce111e9429c" %>

  ## Managed Metadata
  <Taxonomy:TaxonomyFieldControl FieldName="" runat="server" InputFieldLabel=""/>
