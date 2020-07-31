---
description: >-
  Add, copy, delete, change the color, align, and configure Message Start Event
  elements in your Process model.
---

# Message Start Event Element

## Permissions Required

{% hint style="info" %}
### Don't Know What a Message Start Event Element Is?

See [Process Modeling Element Descriptions](process-modeling-element-descriptions.md) for a description of the [Message Start Event](process-modeling-element-descriptions.md#message-start-event) element.
{% endhint %}

Your ProcessMaker user account or group membership must have the following permissions to configure a Message Start Event element in the Process model unless your user account has the **Make this user a Super Admin** setting selected:

* Processes: Edit Processes
* Processes: View Processes

See the [Process](../../../processmaker-administration/permission-descriptions-for-users-and-groups.md#processes) permissions or ask your ProcessMaker Administrator for assistance.

## Add a Message Start Event Element

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-message-start-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to add a Message Start Event element to the Process model:

1. [View your Processes](../../viewing-processes/view-the-list-of-processes/view-your-processes.md#view-all-active-processes). The **Processes** page displays.
2. [Create a new Process](../../viewing-processes/view-the-list-of-processes/create-a-process.md) or click the **Open Modeler** icon![](../../../.gitbook/assets/open-modeler-edit-icon-processes-page-processes.png)to edit the selected Process model. Process Modeler displays.
3. Locate the **Start Event** element in the **Elements and Connectors** palette that is to the left of the Process Modeler canvas. If the [**Hide Menus** button](../navigate-around-your-process-model.md#maximize-the-process-modeler-canvas-view)![](../../../.gitbook/assets/hide-menus-button-process-modeler-processes.png)is enabled, the **Elements and Connectors** palette displays the **Start Event** element's icon![](../../../.gitbook/assets/start-event-element-icon-process-modeler-processes.png).

   ![](../../../.gitbook/assets/start-event-control-process-modeler-processes.png)

4. Drag the element into the Process model canvas where you want to place it. If a Pool element is in your Process model, the Start Timer Event element cannot be placed outside of the Pool element.
5. From the **Elements** drop-down menu, select the **Message Start Event** option. The Message Start Event element displays. ![](../../../.gitbook/assets/message-start-event-selection-process-modeler-designer.png) 

![Message Start Event element](../../../.gitbook/assets/message-start-event-element-process-modeler-designer.png)

After the element is placed into the Process model, you may adjust its location in the following ways:

* Move the element by dragging it to a new location.
* [Select the element with other elements and/or connectors](../select-multiple-process-model-elements-and-connectors.md#select-multiple-process-model-objects), and then move them collectively by dragging them to new locations in relation to one another.
* [Align](../align-and-distribute-process-model-elements-and-connectors.md#align-process-model-objects) and/or [distribute](../align-and-distribute-process-model-elements-and-connectors.md#distribute-process-model-objects) the element in relation to other selected elements and/or [connectors](../model-processes-using-connectors/what-is-a-connector.md).

{% hint style="warning" %}
Moving a Message Start Event element has the following limitations in regards to the following Process model elements:

* **Pool element:** If the Message Start Event element is inside of a [Pool](process-modeling-element-descriptions.md#pool) element, it cannot be moved outside of the Pool element. If you attempt to do so, Process Modeler places the Message Start Event element inside the Pool element closest to where you attempt to move it.
* **Lane element:** If the Message Start Event element is inside of a Lane element, it can be moved to another Lane element in the same Pool element. However, the Message Start Event element cannot be moved outside of the Pool element.
{% endhint %}

## Change the Color of a Message Start Event Element

The Message Start Event element and label have a default green color to indicate that this element is a starting [Request](../../../using-processmaker/requests/what-is-a-request.md) event. After a Message Start Event element is [added to a Process model](add-and-configure-message-start-event-elements.md#add-a-message-start-event-element), its shape and label color can be changed. Element and [connector](../model-processes-using-connectors/what-is-a-connector.md) colors may only be changed individually.

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-message-start-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to change the color and label for a Message Start Event element:

1. [View your Processes](https://processmaker.gitbook.io/processmaker-4-community/-LPblkrcFWowWJ6HZdhC/~/drafts/-LRhVZm0ddxDcGGdN5ZN/primary/designing-processes/viewing-processes/view-the-list-of-processes/view-your-processes#view-all-processes). The **Processes** page displays.
2. Click the **Open Modeler** icon![](../../../.gitbook/assets/open-modeler-edit-icon-processes-page-processes.png)to edit the selected Process model. Process Modeler displays.
3. Select the Message Start Event element to change its color. Available options display above the selected element. ![](../../../.gitbook/assets/change-color-message-start-event-element-process-modeler-designer.png) 
4. Click the **Open Color Palette** icon![](../../../.gitbook/assets/open-color-palette-icon-process-modeler-designer.png). The color palette displays.
5. Do one of the following:
   * **Select a color swatch:** Select one of the color swatches from the color palette. The Message Start Event element and label change to that color.
   * **Specify a custom color:** Click the![](../../../.gitbook/assets/color-selector-swatch-process-modeler-designer.png)icon to display the color selector, and then select a color, enter the [Hex color code](https://www.color-hex.com/), or enter the red, green, blue, and alpha color values for the custom color. The Message Start Event element and label change to that color. ![](../../../.gitbook/assets/color-selector-process-modeler-designer.png) 
   * **Reset to the default color:** Click the![](../../../.gitbook/assets/reset-color-icon-process-modeler-designer.png)icon to reset the Message Start Event element and label to its default color.

## Replace a Message Start Event Element with a Different Starting Request Event Element

After a Message Start Event element is [added to a Process model](add-and-configure-message-start-event-elements.md#add-a-message-start-event-element), you may replace it with a different starting [Request](../../../using-processmaker/requests/what-is-a-request.md) event element:

* [Start Event](process-modeling-element-descriptions.md#start-event) element
* [Start Timer Event](process-modeling-element-descriptions.md#start-timer-event) element
* [Signal Start Event](process-modeling-element-descriptions.md#signal-start-event) element

The selected Message Start Event element is replaced by the default settings and color of the replacing element.

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-message-start-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to replace a Message Start Event element with a different starting Request event element:

1. ​[View your Processes](https://processmaker.gitbook.io/processmaker-4-community/-LPblkrcFWowWJ6HZdhC/~/drafts/-LRhVZm0ddxDcGGdN5ZN/primary/designing-processes/viewing-processes/view-the-list-of-processes/view-your-processes#view-all-processes). The **Processes** page displays.
2. Click the **Open Modeler** icon![](../../../.gitbook/assets/open-modeler-edit-icon-processes-page-processes.png)to edit the selected Process model. Process Modeler displays.
3. Select the Message Start Event element to change to another starting Request event element. Available options display above the selected element.
4. Click the **Elements** icon. The **Elements** drop-down menu displays the starting Request event elements. ![](../../../.gitbook/assets/change-element-message-start-event-process-modeler-designer.png) 
5. Select the element to replace the Message Start Event element. The **Change Type** screen displays to confirm replacing the currently selected element. ![](../../../.gitbook/assets/change-type-screen-process-modeler-designer.png) 
6. Click **Confirm**. The new element replaces the Message Start Event element with its default settings and color.

## Copy a Message Start Event Element

Copying a Message Start Event element copies the original along with its current settings, making it easier and faster to continue designing without adding default elements or [connectors](../model-processes-using-connectors/what-is-a-connector.md) with their default settings.

The copied Message Start Event element displays below the original. Any [Sequence Flow](process-modeling-element-descriptions.md#sequence-flow) and/or [Message Flow](process-modeling-element-descriptions.md#message-flow) elements incoming to or outgoing from the original are not copied.

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-message-start-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to copy a Message Start Event element in your Process model:

1. ​[View your Processes](https://processmaker.gitbook.io/processmaker-4-community/-LPblkrcFWowWJ6HZdhC/~/drafts/-LRhVZm0ddxDcGGdN5ZN/primary/designing-processes/viewing-processes/view-the-list-of-processes/view-your-processes#view-all-processes). The **Processes** page displays.
2. Click the **Open Modeler** icon![](../../../.gitbook/assets/open-modeler-edit-icon-processes-page-processes.png)to edit the selected Process model. Process Modeler displays.
3. Select the Message Start Event element to copy. Available options display above the selected element. ![](../../../.gitbook/assets/copy-message-start-event-element-process-modeler-designer.png) 
4. Click the **Copy Element** icon![](../../../.gitbook/assets/copy-element-icon-process-modeler-designer.png). The Process model element copies. ![](../../../.gitbook/assets/copied-message-start-event-element-process-modeler-designer.png) 

## Delete a Message Start Event Element

Deleting a Process model element also deletes any [Sequence Flow](process-modeling-element-descriptions.md#sequence-flow) and/or [Message Flow](process-modeling-element-descriptions.md#message-flow) elements incoming to or outgoing from that element. For example, if a Process model element is deleted that has both incoming and outgoing Sequence Flow elements, the Sequence Flow elements must be reconnected for the remaining elements/[connectors](../model-processes-using-connectors/what-is-a-connector.md).

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-message-start-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to delete a Message Start Event element from your Process model:

1. ​[View your Processes](https://processmaker.gitbook.io/processmaker-4-community/-LPblkrcFWowWJ6HZdhC/~/drafts/-LRhVZm0ddxDcGGdN5ZN/primary/designing-processes/viewing-processes/view-the-list-of-processes/view-your-processes#view-all-processes). The **Processes** page displays.
2. Click the **Open Modeler** icon![](../../../.gitbook/assets/open-modeler-edit-icon-processes-page-processes.png)to edit the selected Process model. Process Modeler displays.
3. Select the Message Start Event element to delete. Available options display above the selected element. ![](../../../.gitbook/assets/delete-message-start-event-element-process-modeler-designer.png) 
4. Click the **Delete** icon![](../../../.gitbook/assets/remove-icon.png). The Process model element deletes.

## Settings

The Start Timer Event element has the following panels that contain settings:

* **Configuration** panel
  * [Edit the element name](add-and-configure-message-start-event-elements.md#edit-the-element-name)
  * [Select the element from which to listen for a message](add-and-configure-message-start-event-elements.md#select-the-element-from-which-to-listen-for-a-message)
* **Advanced** panel
  * [Edit the element's identifier value](add-and-configure-message-start-event-elements.md#edit-the-elements-identifier-value)

### Configuration Panel Settings

#### Edit the Element Name

An element name is a human-readable reference for a Process element. Process Modeler automatically assigns the name of a Process element with its element type. However, an element's name can be changed.

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-message-start-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to edit the name for a Message Start Event element:

1. Ensure that the **Hide Menus** button![](../../../.gitbook/assets/hide-menus-button-process-modeler-processes.png)is not enabled. See [Maximize the Process Modeler Canvas View](../navigate-around-your-process-model.md#maximize-the-process-modeler-canvas-view).
2. Select the Message Start Event element from the Process model in which to edit its name. Panels to configure this element display.
3. Expand the **Configuration** panel if it is not presently expanded. The **Name** setting displays. This is a required setting. ![](../../../.gitbook/assets/message-start-event-configuration-name-process-modeler-processes.png) 
4. In the **Name** setting, edit the selected element's name and then press **Enter**.

#### Select the Element from Which to Listen for a Message

An Message Start Event element starts a [Request](../../../using-processmaker/requests/what-is-a-request.md) when that element receives a message from either an [Intermediate Message Throw Event](process-modeling-element-descriptions.md#intermediate-message-throw-event) element or a [Message End Event](process-modeling-element-descriptions.md#message-end-event) element \(but not both\) located in a different [Pool](process-modeling-element-descriptions.md#pool) element than the Message Start Event element receiving the message. After the Message Start Event element receives its message, that element triggers. Select from which element to listen for a message based on the Intermediate Message Throw Event or Message End Event element's **Message Name** setting value.

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-message-start-event-elements.md#permissions-required).
{% endhint %}

Follow these steps to select from which element to listen for a message to trigger the Message Start Event element:

1. Ensure that the **Hide Menus** button![](../../../.gitbook/assets/hide-menus-button-process-modeler-processes.png)is not enabled. See [Maximize the Process Modeler Canvas View](../navigate-around-your-process-model.md#maximize-the-process-modeler-canvas-view).
2. Select the Message Start Event element from the Process model in which to select the Process model element from which to listen for a message. Panels to configure this element display.
3. Expand the **Configuration** panel if it is not presently expanded and then locate the **Listen For Message** setting. ![](../../../.gitbook/assets/message-start-event-configuration-listen-process-modeler-processes.png) 
4. From the **Listen For Message** drop-down menu, select from which element to listen for a message based on its **Message Name** setting value.

### Advanced Panel Settings

#### Edit the Element's Identifier Value

Process Modeler automatically assigns a unique value to each Process element added to a Process model. However, an element's identifier value can be changed if it is unique to all other elements in the Process model, including the Process model's identifier value.

{% hint style="info" %}
[Permissions are required to do this](add-and-configure-message-start-event-elements.md#permissions-required).
{% endhint %}

{% hint style="warning" %}
All identifier values for all elements in the Process model must be unique.
{% endhint %}

Follow these steps to edit the identifier value for a Message Start Event element:

1. Ensure that the **Hide Menus** button![](../../../.gitbook/assets/hide-menus-button-process-modeler-processes.png)is not enabled. See [Maximize the Process Modeler Canvas View](../navigate-around-your-process-model.md#maximize-the-process-modeler-canvas-view).
2. Select the Message Start Event element from the Process model in which to edit its identifier value. Panels to configure this element display.
3. Expand the **Advanced** panel if it is not presently expanded. The **Node Identifier** setting displays. This is a required setting. ![](../../../.gitbook/assets/message-start-event-configuration-identifier-process-modeler-processes.png) 
4. In the **Node Identifier** setting, edit the Message Start Event element's identifier to a unique value from all elements in the Process model and then press **Enter**.

## Related Topics

{% page-ref page="process-modeling-element-descriptions.md" %}

{% page-ref page="../../viewing-processes/view-the-list-of-processes/view-your-processes.md" %}

{% page-ref page="../../viewing-processes/view-the-list-of-processes/create-a-process.md" %}

{% page-ref page="../../../using-processmaker/requests/what-is-a-request.md" %}

{% page-ref page="set-and-delete-message-flow-between-elements.md" %}
