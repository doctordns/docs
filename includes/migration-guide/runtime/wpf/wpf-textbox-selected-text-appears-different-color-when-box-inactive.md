### WPF TextBox selected text appears a different color when the text box is inactive

|   |   |
|---|---|
<<<<<<< HEAD
|Details|In .NET 4.5, when a WPF text box control is inactive (it doesn&#39;t have focus), the selected text inside the box will appear a different color than when the control is active.|
|Suggestion|Previous (.NET 4.0) behavior may be restored by setting the <xref:System.Windows.FrameworkCompatibilityPreferences.AreInactiveSelectionHighlightBrushKeysSupported> property to <code>false</code>.|
=======
|Details|In .NET Framework 4.5, when a WPF text box control is inactive (it doesn't have focus), the selected text inside the box will appear a different color than when the control is active.|
|Suggestion|The previous (.NET Framework 4.0) behavior may be restored by setting the <xref:System.Windows.FrameworkCompatibilityPreferences.AreInactiveSelectionHighlightBrushKeysSupported> property to <code>false</code>.|
>>>>>>> upstream/master
|Scope|Edge|
|Version|4.5|
|Type|Runtime|
|Affected APIs|<ul><li><xref:System.Windows.Controls.TextBox?displayProperty=nameWithType></li></ul>|
<<<<<<< HEAD
|Analyzers|<ul><li>CD0004</li></ul>|
=======
>>>>>>> upstream/master

