## Code of some methods
<hr>

### combo box 
`if()` index can `0,1,2,3,4...`
 ```powershell
comboVariable.getSelectedIndex()==

```
` this will be gives the name of Item `
 ```powershell
getSelectedItem()

```
### ignor the space using:
 ```powershell
.trim()

```
### tiktik selector will in textfild
 ```powershell
.grabFocus()

```
### Show popup
 ```powershell
.JOption.showMessageDialog(classname.this,"some text"+label_variable_or_object.getText())

```
   ### Add data in Table ` Defulat object need to crate`
   
 ```powershell
DefaultTableModel objName;

```
then need to initialize into class's constroctor
```powershell
objName= (DefaultTableModel) tableObjeName.getModel();
```
After that in the add even batton method: `DefaultTableModel object name`
```poweshell
objName.insertRow(tableObjeName.getRowCont(),new object[]{
     
     colum1.getText();
     colum2.getText();
     
     });
```
After to onselected:
```poweshell









