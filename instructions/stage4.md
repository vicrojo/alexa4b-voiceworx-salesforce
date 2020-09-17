# Alexa for Business configuration

[![Alexa Skill set up](../images/navigation/1.png)](./stage1.md)[![Accounts set up](../images/navigation/2.png)](./stage2.md)[![Integrating Voicewox.ai with Salesforce](../images/navigation/3.png)](./stage3.md)[![Alexa for Business Configuration and Testing](../images/navigation/current4.png)](./stage4.md)

1. Log in to the AWS Alexa console.

![](../images/a4bconfiguration/1.png)

2. Go to the Alexa for Business console.

![](../images/a4bconfiguration/2.png)

3. Go to the Resources > Skills > Alexa skills store.

![](../images/a4bconfiguration/3.png)

4. In the search texbox, type the word "voiceworx" and hit the Enter key.
5. You will see a skill with name "Sales Force", Developer Voiceworx.ai. Click on the "Enable" button.

![](../images/a4bconfiguration/4.png)

6. Confirm the account linking.

![](../images/a4bconfiguration/6.png)

7. Enter the Alexa Developer account previously created

![](../images/a4bconfiguration/7.png)

8. The skill is now enabled. We need to add it to a Skills group in A4B.

![](../images/a4bconfiguration/8.png)

9. To do so, go to Configuration > Skill groups in the A4B Console.

![](../images/a4bconfiguration/9.png)

10. Click on the "Create skill group" button.

11. Once the skill group was created, click on the group name and then click on the "Add skills button."

![](../images/a4bconfiguration/10-11.png)

![](../images/a4bconfiguration/10-11-2.png)

12. Click on the name of the group you created.

13. Click on the Add Skills Button

![](../images/a4bconfiguration/12.png)

14. Select the voiceworx skill you previously added from the Alexa skill store and click on the Add button

![](../images/a4bconfiguration/14.png)

![](../images/a4bconfiguration/15.png)

15. Click on the Add to room button

16. Select the room(s) where you want to add the Alexa skill group.

![](../images/a4bconfiguration/16.png)

17. Select the Skills Group previously created and click on the "Add" button.

![](../images/a4bconfiguration/17.png)

18. The Alexa skill will be available on the room you selected (including its shared devices)

![](../images/a4bconfiguration/18.png)

19. In on of the shared devices assigned to the room that we configured, invoke the Alexa skill saying "Alexa, open Salesforce". If you hear a welcome message the skill is configured correctly. After the welcome message, you can try the following phrases:

* "Check my sales briefing"
* "Check my pipeline briefing"
* "Check my quota briefing"
* "Check my activities briefing"
* "Check my cases briefing"
* To quit the skill, say "Stop" or "Cancel"
* To ask for assistance, say "Help"

[![Next](../images/navigation/previous.png)](./stage3.md)[![Home](../images/navigation/home.png)](../README.md)