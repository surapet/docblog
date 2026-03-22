You first have to get SharePoint Online Drive information for the Team/SharePoint library you are accessing
-insert SPO Drive Access to be developed-

Get an Excel Workbook
/drives/{drive-id}/items/{item-id}/workbook/worksheets/{worksheet-id}
Get a single cell from an Excel Workbook
/drives/{drive-id}/items/{item-id}/workbook/worksheets/{worksheet-id}/range/cell(row={row},column={column})
Get a range of cells in an Excel Workbook
/drives/{drive-id}/items/{item-id}/workbook/worksheets/{worksheet-id}/range(address='{range}')
Get a Table from an Excel Workbook
/drives/{drive-id}/items/{item-id}/workbook/worksheets/{worksheet-id}/tables/{table-id}
