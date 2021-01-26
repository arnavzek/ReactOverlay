# 🎋 ReactOverlay

## Usage

```
  import ReactOverlay from "./reactOverlay";
  let [dialogData, setDialogData] = useState(null);
  <ReactOverlay data={dialogData} setData={setDialogData}></ReactOverlay>
```

When data prop is null, overlay is set to hidden.

## Format of data
```
    setDialogData({
      message: "🚀 To the sky",
      children: <Acomponent />,
    });
```
