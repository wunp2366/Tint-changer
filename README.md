# Tint Column Tools

An independent Blender 5.3 add-on for editing Sollumz tint palette columns and removing hidden overlapping models from the export hierarchy.

## Install

Download the ZIP from Releases, then choose **Edit > Preferences > Add-ons > Install from Disk** in Blender. Enable **Tint Column Tools**. Sollumz is required to import or export YDRs.

## Tint

Select faces in Edit Mode, return to Object Mode, and open **N > Tint**. Choose a tint modifier or all modifiers and drag **Palette Column**. Click **Apply Tint** to commit the column to the exportable vertex color data. **Cancel Preview** discards the preview. The first slider movement captures the selected faces. To add more faces, cancel, select them, and begin a new preview.

## Duplicate cleanup

Select a drawable or one of its meshes and click **Detach Hidden Duplicates**. The tool compares hidden models to visible siblings, checking face positions, winding, materials, and every populated LOD. It detaches a match from the export hierarchy while preserving its world transform and scene object. The action supports Undo.
