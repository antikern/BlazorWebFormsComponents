The GridView component is meant to emulate the asp:GridView control in markup and is defined in the [System.Web.UI.WebControls.GridView class](https://docs.microsoft.com/en-us/dotnet/api/system.web.ui.webcontrols.gridview?view=netframework-4.8)

## Features supported in Blazor
- Readonly grid
- Bound, Hyperlink, and Template columns

## Web Forms Declarative Syntax

```html
<asp:GridView
    AccessKey="string"
    AllowPaging="True|False"
    AllowSorting="True|False"
    AutoGenerateColumns="True|False"
    AutoGenerateDeleteButton="True|False"
    AutoGenerateEditButton="True|False"
    AutoGenerateSelectButton="True|False"
    BackColor="color name|#dddddd"
    BackImageUrl="uri"
    BorderColor="color name|#dddddd"
    BorderStyle="NotSet|None|Dotted|Dashed|Solid|Double|Groove|Ridge|
        Inset|Outset"
    BorderWidth="size"
    Caption="string"
    CaptionAlign="NotSet|Top|Bottom|Left|Right"
    CellPadding="integer"
    CellSpacing="integer"
    CssClass="string"
    DataKeyNames="string"
    DataMember="string"
    DataSource="string"
    DataSourceID="string"
    EditIndex="integer"
    EmptyDataText="string"
    Enabled="True|False"
    EnableSortingAndPagingCallbacks="True|False"
    EnableTheming="True|False"
    EnableViewState="True|False"
    Font-Bold="True|False"
    Font-Italic="True|False"
    Font-Names="string"
    Font-Overline="True|False"
    Font-Size="string|Smaller|Larger|XX-Small|X-Small|Small|Medium|
        Large|X-Large|XX-Large"
    Font-Strikeout="True|False"
    Font-Underline="True|False"
    ForeColor="color name|#dddddd"
    GridLines="None|Horizontal|Vertical|Both"
    Height="size"
    HorizontalAlign="NotSet|Left|Center|Right|Justify"
    ID="string"
    OnDataBinding="DataBinding event handler"
    OnDataBound="DataBound event handler"
    OnDisposed="Disposed event handler"
    OnInit="Init event handler"
    OnLoad="Load event handler"
    OnPageIndexChanged="PageIndexChanged event handler"
    OnPageIndexChanging="PageIndexChanging event handler"
    OnPreRender="PreRender event handler"
    OnRowCancelingEdit="RowCancelingEdit event handler"
    OnRowCommand="RowCommand event handler"
    OnRowCreated="RowCreated event handler"
    OnRowDataBound="RowDataBound event handler"
    OnRowDeleted="RowDeleted event handler"
    OnRowDeleting="RowDeleting event handler"
    OnRowEditing="RowEditing event handler"
    OnRowUpdated="RowUpdated event handler"
    OnRowUpdating="RowUpdating event handler"
    OnSelectedIndexChanged="SelectedIndexChanged event handler"
    OnSelectedIndexChanging="SelectedIndexChanging event handler"
    OnSorted="Sorted event handler"
    OnSorting="Sorting event handler"
    OnUnload="Unload event handler"
    PageIndex="integer"
    PagerSettings-FirstPageImageUrl="uri"
    PagerSettings-FirstPageText="string"
    PagerSettings-LastPageImageUrl="uri"
    PagerSettings-LastPageText="string"
    PagerSettings-Mode="NextPrevious|Numeric|NextPreviousFirstLast|
        NumericFirstLast"
    PagerSettings-NextPageImageUrl="uri"
    PagerSettings-NextPageText="string"
    PagerSettings-PageButtonCount="integer"
    PagerSettings-Position="Bottom|Top|TopAndBottom"
    PagerSettings-PreviousPageImageUrl="uri"
    PagerSettings-PreviousPageText="string"
    PagerSettings-Visible="True|False"
    PageSize="integer"
    RowHeaderColumn="string"
    runat="server"
    SelectedIndex="integer"
    ShowFooter="True|False"
    ShowHeader="True|False"
    SkinID="string"
    Style="string"
    TabIndex="integer"
    ToolTip="string"
    UseAccessibleHeader="True|False"
    Visible="True|False"
    Width="size"
>
        <AlternatingRowStyle />
        <Columns>
                <asp:BoundField
                    AccessibleHeaderText="string"
                    ApplyFormatInEditMode="True|False"
                    ConvertEmptyStringToNull="True|False"
                    DataField="string"
                    DataFormatString="string"
                    FooterText="string"
                    HeaderImageUrl="uri"
                    HeaderText="string"
                    HtmlEncode="True|False"
                    InsertVisible="True|False"
                    NullDisplayText="string"
                    ReadOnly="True|False"
                    ShowHeader="True|False"
                    SortExpression="string"
                    Visible="True|False"
>
                        <ControlStyle />
                        <FooterStyle />
                        <HeaderStyle />
                        <ItemStyle />
                </asp:BoundField>
                <asp:ButtonField
                    AccessibleHeaderText="string"
                    ButtonType="Button|Image|Link"
                    CausesValidation="True|False"
                    CommandName="string"
                    DataTextField="string"
                    DataTextFormatString="string"
                    FooterText="string"
                    HeaderImageUrl="uri"
                    HeaderText="string"
                    ImageUrl="uri"
                    InsertVisible="True|False"
                    ShowHeader="True|False"
                    SortExpression="string"
                    Text="string"
                    ValidationGroup="string"
                    Visible="True|False"
>
                        <ControlStyle />
                        <FooterStyle />
                        <HeaderStyle />
                        <ItemStyle />
                </asp:ButtonField>
                <asp:CheckBoxField
                    AccessibleHeaderText="string"
                    DataField="string"
                    FooterText="string"
                    HeaderImageUrl="uri"
                    HeaderText="string"
                    InsertVisible="True|False"
                    ReadOnly="True|False"
                    ShowHeader="True|False"
                    SortExpression="string"
                    Text="string"
                    Visible="True|False"
>
                        <ControlStyle />
                        <FooterStyle />
                        <HeaderStyle />
                        <ItemStyle />
                </asp:CheckBoxField>
                <asp:CommandField
                    AccessibleHeaderText="string"
                    ButtonType="Button|Image|Link"
                    CancelImageUrl="uri"
                    CancelText="string"
                    CausesValidation="True|False"
                    DeleteImageUrl="uri"
                    DeleteText="string"
                    EditImageUrl="uri"
                    EditText="string"
                    FooterText="string"
                    HeaderImageUrl="uri"
                    HeaderText="string"
                    InsertImageUrl="uri"
                    InsertText="string"
                    InsertVisible="True|False"
                    NewImageUrl="uri"
                    NewText="string"
                    SelectImageUrl="uri"
                    SelectText="string"
                    ShowCancelButton="True|False"
                    ShowDeleteButton="True|False"
                    ShowEditButton="True|False"
                    ShowHeader="True|False"
                    ShowInsertButton="True|False"
                    ShowSelectButton="True|False"
                    SortExpression="string"
                    UpdateImageUrl="uri"
                    UpdateText="string"
                    ValidationGroup="string"
                    Visible="True|False"
>
                        <ControlStyle />
                        <FooterStyle />
                        <HeaderStyle />
                        <ItemStyle />
                </asp:CommandField>
                <asp:DynamicField
                    AccessibleHeaderText="string"
                    ApplyFormatInEditMode="True|False"
                    ConvertEmptyStringToNull="True|False"
                    DataField="string"
                    DataFormatString="string"
                    FooterText="string"
                    HeaderImageUrl="uri"
                    HeaderText="string"
                    HtmlEncode="True|False"
                    InsertVisible="True|False"
                    NullDisplayText="string"
                    ShowHeader="True|False"
                    UIHint="string"
                    Visible="True|False"
>
                        <ControlStyle />
                        <FooterStyle />
                        <HeaderStyle />
                        <ItemStyle />
                </asp:DynamicField>
                <asp:HyperLinkField
                    AccessibleHeaderText="string"
                    DataNavigateUrlFields="string"
                    DataNavigateUrlFormatString="string"
                    DataTextField="string"
                    DataTextFormatString="string"
                    FooterText="string"
                    HeaderImageUrl="uri"
                    HeaderText="string"
                    InsertVisible="True|False"
                    NavigateUrl="uri"
                    ShowHeader="True|False"
                    SortExpression="string"
                    Target="string|_blank|_parent|_search|_self|_top"
                    Text="string"
                    Visible="True|False"
>
                        <ControlStyle />
                        <FooterStyle />
                        <HeaderStyle />
                        <ItemStyle />
                </asp:HyperLinkField>
                <asp:ImageField
                    AccessibleHeaderText="string"
                    AlternateText="string"
                    ConvertEmptyStringToNull="True|False"
                    DataAlternateTextField="string"
                    DataAlternateTextFormatString="string"
                    DataImageUrlField="string"
                    DataImageUrlFormatString="string"
                    FooterText="string"
                    HeaderImageUrl="uri"
                    HeaderText="string"
                    InsertVisible="True|False"
                    NullDisplayText="string"
                    NullImageUrl="uri"
                    ReadOnly="True|False"
                    ShowHeader="True|False"
                    SortExpression="string"
                    Visible="True|False"
>
                        <ControlStyle />
                        <FooterStyle />
                        <HeaderStyle />
                        <ItemStyle />
                </asp:ImageField>
                <asp:TemplateField
                    AccessibleHeaderText="string"
                    ConvertEmptyStringToNull="True|False"
                    FooterText="string"
                    HeaderImageUrl="uri"
                    HeaderText="string"
                    InsertVisible="True|False"
                    ShowHeader="True|False"
                    SortExpression="string"
                    Visible="True|False"
>
                            <ControlStyle />
                            <FooterStyle />
                            <HeaderStyle />
                            <ItemStyle />
                        <AlternatingItemTemplate>
                            <!-- child controls -->
                        </AlternatingItemTemplate>
                        <EditItemTemplate>
                            <!-- child controls -->
                        </EditItemTemplate>
                        <FooterTemplate>
                            <!-- child controls -->
                        </FooterTemplate>
                        <HeaderTemplate>
                            <!-- child controls -->
                        </HeaderTemplate>
                        <InsertItemTemplate>
                            <!-- child controls -->
                        </InsertItemTemplate>
                        <ItemTemplate>
                            <!-- child controls -->
                        </ItemTemplate>
                </asp:TemplateField>
        </Columns>
        <EditRowStyle />
        <EmptyDataRowStyle />
        <EmptyDataTemplate>
            <!-- child controls -->
        </EmptyDataTemplate>
        <FooterStyle />
        <HeaderStyle />
        <PagerSettings
            FirstPageImageUrl="uri"
            FirstPageText="string"
            LastPageImageUrl="uri"
            LastPageText="string"
            Mode="NextPrevious|Numeric|NextPreviousFirstLast|
                NumericFirstLast"
            NextPageImageUrl="uri"
            NextPageText="string"
            OnPropertyChanged="PropertyChanged event handler"
            PageButtonCount="integer"
            Position="Bottom|Top|TopAndBottom"
            PreviousPageImageUrl="uri"
            PreviousPageText="string"
            Visible="True|False"
        />
        <PagerStyle />
        <PagerTemplate>
            <!-- child controls -->
        </PagerTemplate>
        <RowStyle />
        <SelectedRowStyle />
</asp:GridView>
```

## Blazor Syntax

Currently, not every syntax element of Web Forms GridView is supported. In the meantime, the following GridView in Blazor syntax will only include the implemented ones. **Non-implemented elements will be included later**.

``` html
<GridView
    runat="server"
    AutoGenerateColumns=bool
    CssClass=string
    DataKeyNames=string
    DataSource=IEnumerable
    EmptyDataText=string
    Enabled=bool
    ID=string
    Items=IEnumerable
    ItemType=Type
    OnDataBinding=EventCallBack
    OnDataBound=EventCallBack
    OnItemDataBound=EventCallBack
    OnInit=EventCallBack
    OnLoad=EventCallBack
    OnPreRender=EventCallBack
    OnUnload=EventCallBack
    OnDisposed=EventCallBack
    SelectMethod=SelectHandler
    TabIndex=int
    Visible=bool
>
    <Columns>
        <BoundField
                    DataField=string
                    DataFormatString=string
                    HeaderText=string
                    Visible=bool
        >
        </BoundField>
        <HyperLinkField
            AccessibleHeaderText="string"
            DataNavigateUrlFields="string"
            DataNavigateUrlFormatString="string"
            DataTextField="string"
            DataTextFormatString="string"
            HeaderText="string"
            NavigateUrl="uri"
            Target="string|_blank|_parent|_search|_self|_top"
            Text="string"
            Visible="True|False">
        </HyperLinkField>
        <TemplateField
                 HeaderText=string
                 Visible=bool
        >
            <ItemTemplate Context="Item">
                <!-- Child Content -->
            <ItemTemplate>
        </TemplateField>
    </Columns>
</GridView>

```
