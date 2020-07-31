---
description: >-
  Add, copy, delete, change the color, and configure Boundary Message Event
  elements in your Process model.
---

# Boundary Message Event Element

## Permissions Required

{% hint style="info" %}
### Don't Know What a Boundary Message Event Element Is?

See [Process Modeling Element Descriptions](process-modeling-element-descriptions.md) for a description of the [Boundary Message Event](process-modeling-element-descriptions.md#boundary-message-event) element.
{% endhint %}

Your ProcessMaker user account or group membership must have the following permissions to configure a Boundary Message Event element in the Process model unless your user account has the **Make this user a Super Admin** setting selected:

* Processes: Edit Processes
* Processes: View Processes

See the [Process](../../../processmaker-administration/permission-descriptions-for-users-and-groups.md#processes) permissions or ask your ProcessMaker Administrator for assistance.

## Add a Boundary Message Event Element

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-boundary-message-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to add a Boundary Message Event element to the Process model:

1. [View your Processes](../../viewing-processes/view-the-list-of-processes/view-your-processes.md#view-all-active-processes). The **Processes** page displays.
2. [Create a new Process](../../viewing-processes/view-the-list-of-processes/create-a-process.md) or click the **Open Modeler** icon![](../../../.gitbook/assets/open-modeler-edit-icon-processes-page-processes.png)to edit the selected Process model. Process Modeler displays.
3. Add the following Process model element or [connector](../model-processes-using-connectors/what-is-a-connector.md) to your Process model in which to associate with the Boundary Error Event element:
   * [Sub Process](add-and-configure-sub-process-elements.md#add-a-sub-process-element) element
   * [Actions By Email](../model-processes-using-connectors/available-connectors-from-processmaker/actions-by-email-connector.md) connector \(requires the [Actions By Email package](../../../package-development-distribution/package-a-connector/actions-by-email-package.md)\)
4. From the **Boundary Events** drop-down menu, select the **Boundary Message Event** option. The Boundary Message Event element displays on the top of its associating element/connector. ![](../../../.gitbook/assets/boundary-message-event-selection-process-modeler-designer.png) 

![Boundary Message Event element associated with a Sub Process element](../../../.gitbook/assets/boundary-message-event-element-process-modeler-designer.png)

After placing the Boundary Message Event element, you may drag it to an adjacent side of its associating element/connector. Since Process Modeler displays labels at the bottom of Process model elements and connectors, the Boundary Message Event element displays best at the bottom of its associating element.

## Change the Color of a Boundary Message Event Element

The Boundary Message Event element and label are black-colored by default. After a Boundary Message Event element is [added to a Process model](add-and-configure-boundary-signal-event-elements.md#add-a-boundary-signal-event-element), its shape and label color can be changed. Element and [connector](../model-processes-using-connectors/what-is-a-connector.md) colors may only be changed individually.

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-boundary-message-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to change the color and label for a Boundary Message Event element:

1. [View your Processes](https://processmaker.gitbook.io/processmaker-4-community/-LPblkrcFWowWJ6HZdhC/~/drafts/-LRhVZm0ddxDcGGdN5ZN/primary/designing-processes/viewing-processes/view-the-list-of-processes/view-your-processes#view-all-processes). The **Processes** page displays.
2. Click the **Open Modeler** icon![](../../../.gitbook/assets/open-modeler-edit-icon-processes-page-processes.png)to edit the selected Process model. Process Modeler displays.
3. Select the Boundary Message Event element to change its color. Available options display above the selected element. ![](../../../.gitbook/assets/change-color-boundary-message-event-element-process-modeler-designer.png) 
4. Click the **Open Color Palette** icon![](../../../.gitbook/assets/open-color-palette-icon-process-modeler-designer.png). The color palette displays.
5. Do one of the following:
   * **Select a color swatch:** Select one of the color swatches from the color palette. The Boundary Message Event element and label change to that color.
   * **Specify a custom color:** Click the![](../../../.gitbook/assets/color-selector-swatch-process-modeler-designer.png)icon to display the color selector, and then select a color, enter the [Hex color code](https://www.color-hex.com/), or enter the red, green, blue, and alpha color values for the custom color. The Boundary Message element and label change to that color. ![](../../../.gitbook/assets/color-selector-process-modeler-designer.png) 
   * **Reset to the default color:** Click the![](../../../.gitbook/assets/reset-color-icon-process-modeler-designer.png)icon to reset the Boundary Message Event element and label to its default color.

## Delete a Boundary Message Event Element

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-boundary-message-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to delete a Boundary Message Event element from your Process model:

1. ​[View your Processes](https://processmaker.gitbook.io/processmaker-4-community/-LPblkrcFWowWJ6HZdhC/~/drafts/-LRhVZm0ddxDcGGdN5ZN/primary/designing-processes/viewing-processes/view-the-list-of-processes/view-your-processes#view-all-processes). The **Processes** page displays.
2. Click the **Open Modeler** icon![](../../../.gitbook/assets/open-modeler-edit-icon-processes-page-processes.png)to edit the selected Process model. Process Modeler displays.
3. Select the Boundary Message Event element to delete. Available options display above the selected element. ![](../../../.gitbook/assets/delete-boundary-message-event-element-process-modeler-designer.png) 
4. Click the **Delete** icon![](../../../.gitbook/assets/remove-icon.png). The Process model element deletes.

## Settings

The Boundary Message Event element has the following panels that contain settings:

* **Configuration** panel
  * [Edit the element name](add-and-configure-boundary-message-event-elements.md#edit-the-element-name)
  * [Indicate to interrupt the best-case scenario workflow](add-and-configure-boundary-message-event-elements.md#indicate-to-interrupt-the-best-case-scenario-workflow)
* **Advanced** panel
  * [Edit the element's identifier value](add-and-configure-boundary-message-event-elements.md#edit-the-elements-identifier-value)

### Configuration Panel Settings

#### Edit the Element Name

An element name is a human-readable reference for a Process element. Process Modeler automatically assigns the name of a Process element with its element type. However, an element's name can be changed.

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-boundary-message-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to edit the name for a Boundary Message Event element:

1. Ensure that the **Hide Menus** button![](../../../.gitbook/assets/hide-menus-button-process-modeler-processes.png)is not enabled. See [Maximize the Process Modeler Canvas View](../navigate-around-your-process-model.md#maximize-the-process-modeler-canvas-view).
2. Select the Boundary Message Event element from the Process model in which to edit its name. Panels to configure this element display.
3. Expand the **Configuration** panel if it is not presently expanded. The **Name** setting displays. This is a required setting. ![](../../../.gitbook/assets/boundary-message-event-configuration-name-process-modeler-designer.png) 
4. In the **Name** setting, edit the selected element's name and then press **Enter**.

#### Indicate to Interrupt the Best-Case Scenario Workflow

Indicate whether the Boundary Message Event element interrupts the best-case scenario workflow:

* **Interrupting workflow:** When workflow routes through the Boundary Message Event element, workflow is interrupted and does not route through the best-case scenario. As highlighted in the example below, workflow routes through the Boundary Message Event element if that element receives a message from the child Request. ![](../../../.gitbook/assets/boundary-message-event-interrupting-example.png) 
* **Non-interrupting workflow:** Workflow routes both through the Boundary Message Event element and the best-case scenario, thereby creating parallel workflow in that Request. As highlighted in the example below, workflow routes through the Boundary Message Event element if that element receives a message from the child Request; however, after the child Request completes and workflow resumes in the parent Request, the Sub Process element completes and routes through the best-case scenario. ![](../../../.gitbook/assets/boundary-message-event-non-interrupting-example.png)

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-boundary-message-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to indicate if this Boundary Message Event element interrupts the best-case scenario workflow when it triggers:

1. Ensure that the **Hide Menus** button![](../../../.gitbook/assets/hide-menus-button-process-modeler-processes.png)is not enabled. See [Maximize the Process Modeler Canvas View](../navigate-around-your-process-model.md#maximize-the-process-modeler-canvas-view).
2. Select the Boundary Message Event element from the Process model in which to indicate if it interrupts the best-case scenario workflow. Panels to configure this element display.
3. Expand the **Configuration** panel if it is not presently expanded, and then locate the **Interrupting** setting. ![](../../../.gitbook/assets/interrupting-boundary-event-process-modeler-designer.png) 
4. From the **Interrupting** checkbox, indicate whether this Boundary Message Event element interrupts the best-case scenario workflow when it triggers. When the **Interrupting** checkbox is selected, which is the default setting, this element interrupts the best-case scenario workflow.

### Advanced Panel Settings

#### Edit the Element's Identifier Value

Process Modeler automatically assigns a unique value to each Process element added to a Process model. However, an element's identifier value can be changed if it is unique to all other elements in the Process model, including the Process model's identifier value.

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-boundary-message-event-elements.md#permissions-required).
{% endhint %}

{% hint style="warning" %}
All identifier values for all elements in the Process model must be unique.
{% endhint %}

Follow these steps to edit the identifier value for a Boundary Message Event element:

1. Ensure that the **Hide Menus** button![](../../../.gitbook/assets/hide-menus-button-process-modeler-processes.png)is not enabled. See [Maximize the Process Modeler Canvas View](../navigate-around-your-process-model.md#maximize-the-process-modeler-canvas-view).
2. Select the Boundary Message Event element from the Process model in which to edit its identifier value. Panels to configure this element display.
3. Expand the **Advanced** panel if it is not presently expanded. The **Node Identifier** setting displays. This is a required setting. ![](../../../.gitbook/assets/boundary-message-event-configuration-identifier-process-modeler-processes.png) 
4. In the **Node Identifier** setting, edit the Boundary Message Event element's identifier to a unique value from all elements in the Process model and then press **Enter**.

## Related Topics

{% page-ref page="process-modeling-element-descriptions.md" %}

{% page-ref page="add-and-configure-sub-process-elements.md" %}
