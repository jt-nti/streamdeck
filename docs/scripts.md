# Scripts

Apple Scripts used with the **System: Open** action

## WebexShare.scpt

```
tell application "Meeting Center"
	activate
	tell application "System Events"
		keystroke "k" using {option down, command down}
	end tell
end tell
```

## WebexToggleMute.scpt

```
tell application "Meeting Center"
	activate
	tell application "System Events"
		keystroke "m" using {shift down, command down}
	end tell
end tell
```

## WebexEndMeeting.scpt

```
tell application "Meeting Center"
	activate
	tell application "System Events"
		keystroke "l" using {command down}
	end tell
end tell
```

