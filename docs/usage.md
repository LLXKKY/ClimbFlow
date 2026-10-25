# ClimbFlow Usage Guide

ClimbFlow is a Rhino 8 plugin designed to support the panelization workflow for climbing wall design.

This guide introduces the main workflow, from preparing the 3D model to reviewing panel layouts and exporting the final outputs.

## 1. Overview

ClimbFlow organizes the workflow into four stages:

1. Prepare the model
2. Generate panel layouts
3. Review and adjust the results
4. Export the outputs

The workflow combines automated generation with manual review, allowing users to inspect and refine the results before exporting.

## 2. Prepare the Model

Before starting:

- Open your climbing wall model in Rhino 8.
- Check that the model geometry is suitable for the intended panelization workflow.
- Save a copy of your original model before making changes.

Start ClimbFlow using the launch method provided by your installed version.

## 3. Generate Panel Layouts

Use the panelization workflow to generate individual panels from the climbing wall geometry and arrange them within the available sheet boundaries.

ClimbFlow is designed around standard sheet dimensions of **1220 × 2440 mm**. Confirm the configured dimensions and units before generating a layout.

After generation, review the resulting panel geometry and layout statistics, including the number of sheets used.

## 4. Review and Adjust

Generated layouts should be reviewed before export.

Depending on the result, you can:

- Inspect the panel arrangement.
- Manually adjust panel placement when necessary.
- Continue with the current layout if it is acceptable.
- Regenerate the layout if you want to explore another result.

Automated layout generation does not guarantee the minimum possible number of sheets. Manual adjustments may improve material utilization.

Before proceeding, verify that the panel outlines fit within the intended sheet boundaries and that the geometry matches your design requirements.

## 5. Export the Outputs

ClimbFlow supports two main output types.

### DXF Files

Export the 2D panel layout as DXF files for downstream fabrication workflows.

Before sending the files for fabrication, check:

- Drawing units and dimensions.
- Panel boundaries and geometry.
- Sheet layout and panel identification.
- Compatibility with your downstream fabrication workflow.

### Numbered 3D Installation Guide

Export a numbered 3D reference to help identify individual panels and understand their positions during installation.

Use the reference alongside the corresponding panel layout and fabrication files.

## 6. Recommended Workflow

For a reliable result, follow this sequence:

1. Prepare and save the original Rhino model.
2. Generate the initial panelization and layout.
3. Review the layout statistics and inspect the geometry.
4. Adjust panel placement or regenerate when necessary.
5. Verify the final panel boundaries and dimensions.
6. Export the DXF files and numbered 3D installation reference.
7. Check the exported files before fabrication or installation.

## 7. Troubleshooting and Feedback

If something does not work as expected:

- Record the step where the problem occurred.
- Note any error messages.
- Capture a screenshot of the relevant Rhino interface.
- If an error occurs in Rhino, copy the relevant command history from the F2 window.

These details help reproduce the issue and improve future versions of ClimbFlow.

## 8. Beta Notice

ClimbFlow is currently in beta. Generated layouts may require manual inspection and adjustment.

Always verify geometry, dimensions, sheet utilization, and exported files before using them for fabrication or installation.

## Related Documentation

- [Installation Guide](installation.md)
- [Project Overview](../README.md)
