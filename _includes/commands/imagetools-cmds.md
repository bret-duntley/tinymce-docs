
| Command                | Description                                          |
| ---------------------- | ---------------------------------------------------- |
| mceEditImage           | Opens the image tools editing dialog.                         |
| mceImageRotateRight    | Rotates selected image 90 degrees clockwise.         |
| mceImageRotateLeft     | Rotates selected image 90 degrees counter clockwise. |
| mceImageFlipVertical   | Flips selected image vertically.                     |
| mceImageFlipHorizontal | Flips selected image horizontally.                   |

**Examples**

```js
tinymce.activeEditor.execCommand('mceEditImage');
tinymce.activeEditor.execCommand('mceImageRotateRight');
tinymce.activeEditor.execCommand('mceImageRotateLeft');
tinymce.activeEditor.execCommand('mceImageFlipVertical');
tinymce.activeEditor.execCommand('mceImageFlipHorizontal');
```
