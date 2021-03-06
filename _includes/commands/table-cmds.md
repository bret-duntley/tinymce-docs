
| Command                 | Description                                     |
| ----------------------- | ----------------------------------------------- |
| mceTableSplitCells      | Splits the current merged table cell.           |
| mceTableMergeCells      | Merges the selected cells.                      |
| mceTableInsertRowBefore | Inserts a row before the current row.           |
| mceTableInsertRowAfter  | Inserts a row after the current row.            |
| mceTableInsertColBefore | Inserts a column before the current column.     |
| mceTableInsertColAfter  | Inserts a column after the current column.      |
| mceTableDeleteCol       | Deletes the current column.                     |
| mceTableDeleteRow       | Deletes the current row.                        |
| mceTableCutRow          | Cuts the current row into the clipboard.      |
| mceTableCopyRow         | Copies the current row into the clipboard.    |
| mceTablePasteRowBefore  | Paste the clipboard row before the current row. |
| mceTablePasteRowAfter   | Paste the clipboard row after the current row.  |
| mceTableDelete          | Deletes the current table.                      |
| mceInsertTable          | Opens the insert/edit table dialog.                  |
| mceTableProps           | Opens the Table Properties dialog.              |
| mceTableRowProps        | Opens the table row properties dialog.          |
| mceTableCellProps       | Opens the table cell properties dialog.         |

**Examples**

```js
tinymce.activeEditor.execCommand('mceTableSplitCells');
tinymce.activeEditor.execCommand('mceTableMergeCells');
tinymce.activeEditor.execCommand('mceTableInsertRowBefore');
tinymce.activeEditor.execCommand('mceTableInsertRowAfter');
tinymce.activeEditor.execCommand('mceTableInsertColBefore');
tinymce.activeEditor.execCommand('mceTableInsertColAfter');
tinymce.activeEditor.execCommand('mceTableDeleteCol');
tinymce.activeEditor.execCommand('mceTableDeleteRow');
tinymce.activeEditor.execCommand('mceTableCutRow');
tinymce.activeEditor.execCommand('mceTableCopyRow');
tinymce.activeEditor.execCommand('mceTablePasteRowBefore');
tinymce.activeEditor.execCommand('mceTablePasteRowAfter');
tinymce.activeEditor.execCommand('mceTableDelete');
tinymce.activeEditor.execCommand('mceInsertTable');
tinymce.activeEditor.execCommand('mceTableProps');
tinymce.activeEditor.execCommand('mceTableRowProps');
tinymce.activeEditor.execCommand('mceTableCellProps');
```
