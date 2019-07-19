# Tracking Code Parser
A proof of concept for a pattern based parser to find tracking code strings and turn them into urls where tracking information can be found.

Intended for use with barcode scanners, put the cursor in the text field of the proof of concept, and scan barcodes (in keyboard entry mode of your barcode scanner with newlines enabled, which is typically the default settings).

View source to see how the patterns are defined.

Idea is that in an acutal production setting you might have patterns created on-the-fly when a barcode is scanned and nothing matches the user is asked to enter the tracking URL, then you can use some smarts to convert the barcode into something resembling a useful pattern - I suspect that by-and-large just replacing all digits with _ would be sufficient in the majority of cases.
