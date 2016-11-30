# overkill-lua-syntax
Custom Lua syntax for Sublime Text that includes preprocessor highlighting.

Comes with Monokai theme (Preferences > Color Scheme > Overkill Lua Syntax > MonokaiOverkill) with the correct preprocessor meta tags. If you want to add them to your theme then add these lines:
```
<!-- Overkill Software meta tags -->
<dict>
	<key>scope</key>
	<string>meta.overkill, meta.overkill.preprocessor</string>
	<key>settings</key>
	<dict>
		<key>foreground</key>
		<string>#66D9EF</string>
	</dict>
</dict>
<dict>
	<key>scope</key>
	<string>meta.overkill.preprocessor.tag</string>
	<key>settings</key>
	<dict>
		<key>foreground</key>
		<string>#F92672</string>
	</dict>
</dict>
<dict>
	<key>scope</key>
	<string>meta.overkill.preprocessor.error</string>
	<key>settings</key>
	<dict>
		<key>foreground</key>
		<string>#FF0000</string>
	</dict>
</dict>
<!-- End Overkill tags -->
```
