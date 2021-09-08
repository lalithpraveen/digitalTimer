?**Live link** https://strawhattimer.ccbp.tech/

In this practice I built a **Digital Timer** by applying the concepts I have learned till now.

### Refer to image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/digital-timer-output.gif" alt="Digital Timer Output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)" />
</div>
<br/>

### Design Files

<details>
<summary>Click to view the Design Files</summary>

- [Extra Small (Size < 576px), Small (Size >= 576px)](https://assets.ccbp.in/frontend/content/react-js/digital-timer-sm-output.png)
- [Medium (Size >= 768px), Large (Size >= 992px) and Extra Large (Size >= 1200px)](https://assets.ccbp.in/frontend/content/react-js/digital-timer-lg-output.png)

</details>


### Project Details

<details>
<summary>Click to view the Functionality  added</summary>

#### Add Functionality

The app must have the following functionalities

- When the **Start** button is clicked
  - The **Start** text should change to **Pause** text
  - The **play icon** should be replaced by **pause icon**
  - The **Timer** status should change to **Running**
  - The **Timer** should start running backward from the timer limit value set
  - If the **Timer** has been paused after starting, it should resume from where it was paused
  - Both the **Plus** and **Minus** buttons should be disabled
- When the **Pause** button is clicked
  - The **Pause** text should change to **Start** text
  - The **pause icon** should be replaced by **play icon**
  - The **Timer** should stop running backward
  - The **Timer** status should change to **Paused**
  - Both the **Plus** and **Minus** buttons should be disabled
- When the button with **Plus** is clicked
  - The timer limit value should increase by 1 minute
  - The **Timer** should display time with the increased timer limit value
- When the button with **Minus** is clicked
  - The timer limit value should decrease by 1 minute
  - The **Timer** should display time with the decreased timer limit value
- When the timer limit value is modified by clicking **Plus** or **Minus** button then the clicking on **Start** button should start the Timer with modified value
- When the **Timer** ends (displays **00:00**)
  - The **Pause** text should change to **Start** text
  - The **pause icon** should be replaced by **play icon**
  - The **Timer** should stop running backward
  - The **Timer** status should change to **Paused**
- After completion of **Timer**, when the **Start** button is clicked
  - The **Start** text should change to **Pause** text
  - The **play icon** should be replaced by **pause icon**
  - The **Timer** should start running backward from the current timer limit value.
  - The **Timer** status should change to **Running**
- When the **Reset** button is clicked then
  - The **Pause** text should change to **Start** text
  - The **pause icon** should be replaced by **play icon**
  - The **Timer** should stop running backward
  - The **Timer** status should change to **Paused**
  - Initial **Timer** limit value should be displayed
  - Both the **Plus** and **Minus** buttons should be enabled

</details>


<br/>

### Resources

<details>
<summary>Image URLs</summary>

#### Images

- [https://assets.ccbp.in/frontend/react-js/digital-timer-elapsed-bg.png](https://assets.ccbp.in/frontend/react-js/digital-timer-elapsed-bg.png)
- [https://assets.ccbp.in/frontend/react-js/play-icon-img.png](https://assets.ccbp.in/frontend/react-js/play-icon-img.png)  alt text should be `play icon`
- [https://assets.ccbp.in/frontend/react-js/pause-icon-img.png](https://assets.ccbp.in/frontend/react-js/pause-icon-img.png)  alt text should be `pause icon`
- [https://assets.ccbp.in/frontend/react-js/reset-icon-img.png](https://assets.ccbp.in/frontend/react-js/reset-icon-img.png) alt text should be `reset icon`
</details>

<details>
<summary>Colors</summary>

#### Colors

<div style="background-color: #ffffff ; width: 150px; padding: 10px; color: black">Hex: #ffffff</div>
<div style="background-color: #cffcf1 ; width: 150px; padding: 10px; color: black">Hex: #cffcf1</div>
<div style="background-color: #1e293b ; width: 150px; padding: 10px; color: white">Hex: #1e293b</div>
<div style="background-color: #0f172a ; width: 150px; padding: 10px; color: white">Hex: #0f172a</div>
<div style="background-color: #defafe ; width: 150px; padding: 10px; color: black">Hex: #defafe</div>
<div style="background-color: #00d9f5 ; width: 150px; padding: 10px; color: white">Hex: #00d9f5</div>

</details>

#### Font-families

- Roboto


