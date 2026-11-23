# WWF Raw 2002 — Android / Godot research project

Work-in-progress extraction and Godot adaptation pipeline for the installer archive supplied by the user.

## Verified so far
- The uploaded archive is a ZIP containing an installer folder `Raw` with `data1.cab`, `data1.hdr`, `data2.cab`, `Setup.exe`, and installer support files.
- Header strings include names such as `FF.XPK`, `IF.XPK`, `MF.XPK`, `SF.XPK`, `TEX.XPK`, `TF.XPK`, and `WF.XPK`. These are only clues; assets have not yet been extracted or identified.
- No character models or animation files have been verified or converted.

## Next
1. Upload the original installer ZIP to a private release or accessible file host, or place it in the repository's `source/` folder if under GitHub's file-size limits.
2. Run the workflow in Actions.
3. Inspect the artifact inventory/logs to determine the container formats.
4. Implement and test parsers/converters before naming outputs as FBX/GLB.

Please avoid publishing copyrighted game assets unless you have permission.
