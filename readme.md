# 🎋 ReactOverlay

✓ Dark Mode 

## Usage

```
  import ReactOverlay from "./reactOverlay";
  
  let [dialogData, setDialogData] = useState(null);
  
  return <ReactOverlay data={dialogData} setData={setDialogData}></ReactOverlay>
```

When data prop is null, overlay is set to hidden.

## Make the dialog visible
```
    setDialogData({
      message: "🚀 To the sky",
      children: <Acomponent />,
    });
```

## Make the dialog invisible
```
    setDialogData(null);
```
