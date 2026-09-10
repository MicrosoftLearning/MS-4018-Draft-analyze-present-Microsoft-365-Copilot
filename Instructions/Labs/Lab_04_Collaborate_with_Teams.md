---
lab:
  title: 'Lab 4: Manage collaboration from start to finish'
  description: Microsoft Copilot – Use Copilot in Teams and Outlook to prepare for and manage team collaboration.
  level: Lab 200
  duration: '30'
  islab: true
  status: 'released'
  targetDate: 2026-12-31
  primarytopics:
    - Microsoft 365
    - Microsoft Copilot
---

# Lab 4 - Manage collaboration from start to finish

Imagine you're a product manager at Contoso. Your team is preparing for the Contoso Connect product launch. You need to align the team on priorities, build context from channel conversations, and schedule a structured planning meeting. In this lab, you use Copilot in Teams and Outlook to prepare before the meeting ever starts.

> [!IMPORTANT]
> To complete this lab, you must have a Microsoft 365 Copilot license and access to Microsoft Teams and Outlook. All parts can be completed fully in the online apps without joining or starting a live meeting.

#### Exercise 1 - Draft and refine a channel message

Before scheduling the meeting, you want to share context and set expectations with your team in the project channel.

1. Open Microsoft Teams by navigating to +++https://teams.cloud.microsoft+++.

1. If the **Get to know Teams** dialog appears, select **Get Started** and close the dialog.

1. In **Chat**, select **See all your teams**.

1. Select **Create team**, and configure the new team as follows:
    - Team name: +++Contoso Connect Launch+++
    - Description: leave blank
    - Team type and sensitivity: **Private**, **None**
    - First channel name: +++Launch Planning+++

1. Select **Create**, then select **Skip** when prompted to add members.

1. Select **Post in channel** to open the message composer in the **Launch Planning** channel.

1. Paste the following text into the message box:

    +++Hi team! As we gear up for the Contoso Connect product launch, I want to make sure we're all aligned on priorities. I have a few ideas to share and I'd love to hear your thoughts on what will resonate most with our customers.+++

1. Before posting, select the Pen (**Rewrite with Copilot**) icon below the message box.

1. Select **Rewrite** to generate an improved version. Use the left and right arrows to review alternate versions.

1. Select **Adjust**, then under **Make it sound** choose **Enthusiastic** to change the tone of the message.

1. Copilot provides each update as a separate version. Use the left and right arrows to review the versions, and select the one you prefer.

1. Select **Replace**, and then select **Post** to publish the message.

#### Exercise 2 - Build channel context and summarize the thread

Channel Agent can summarize a channel thread to help you catch up on what was discussed. In this exercise, you'll add a few messages to build some context, then use Channel Agent to get a quick overview.

1. With the **Launch Planning** channel still open, post two or three additional messages to build out the thread. For example:

    - +++One idea is running a live demo event for our top enterprise customers.+++
    - +++Early access pricing worked well for our last launch — we should revisit that.+++
    - +++I'll reach out to marketing about the collateral timeline. Can someone check on demo environment availability?+++

1. After posting the messages, select the **Open agents and bots** icon at the top-right of the channel.

1. In the **Agents and bots** pane, next to **Channel Agent**, select **Add**.

1. In the Channel Agent post, select **Ask me a question**.

1. Enter the following prompt:

    +++What ideas and open questions came up in this thread?+++

1. Review the summary. Select a numbered citation to view the source message in the channel.

1. Enter a follow-up prompt:

    +++Create a short list of discussion topics I could use as a meeting agenda.+++

    Keep this list handy. You'll use it in the next exercise.

#### Exercise 3 - Schedule a meeting with Facilitator enabled

Now you'll create the meeting invite in Outlook, add an agenda, and turn on Facilitator so the meeting is set up to run effectively.

1. Open Microsoft Outlook from your browser by navigating to +++https://outlook.office.com+++.

1. Open **Calendar** and select **New event**.

1. Add a title such as +++Contoso Connect Launch Planning+++ and set a time for later today or tomorrow.

1. Make sure **Teams meeting** is toggled on.

1. In the meeting description, type a short agenda using the topics Channel Agent surfaced in Exercise 2. For example:

    +++Agenda: Customer engagement ideas (10 min), Launch timeline review (15 min), Demo environment check (5 min), Task assignments (10 min), Wrap-up (5 min)+++

    > [!TIP]
    > You can also let Copilot draft this for you. Select the Copilot icon in the upper-right corner of the New event window, and enter: *Draft a meeting description for a product launch planning session covering customer engagement ideas, timeline review, and task assignments.*

1. Select **Options** to open the **Meeting options** dialog.

1. Under **Copilot and other AI**, confirm **Allow Copilot and Facilitator** is set to **During and after the meeting**.

1. Turn on the **Facilitator** toggle, then select **Apply**.

1. Select **Save** to save the invite.

    When at least one non-organizer participant joins the meeting, Facilitator automatically posts the agenda to the meeting chat and displays a timer on the meeting stage.

#### Exercise 4 - Prepare for the meeting in Outlook

With the event created, use Copilot to review context and get ready before you join.

1. Open the meeting event from your Outlook calendar.

1. Look for the **Prepare for this meeting** section near the top of the event form. Select **Show more** to see the summary Copilot has assembled from related emails, documents, and chat history.

   > [!NOTE]
   > In a fresh environment with no prior email history, chat activity, or shared files connected to the meeting, the **Prepare for this meeting** section may not appear or may display limited results. This is expected behavior. Copilot generates meeting preparation content only when sufficient context is available. If the section isn't displayed, consider this lab complete.

1. Select one of the suggested prompts, or enter your own in the Copilot chat pane:

    +++What should I know about the agenda or attendees before this meeting?+++

1. Enter a follow-up prompt:

    +++Draft a brief opening statement I can use to kick off the meeting.+++

1. Review the response. Notice how Copilot draws on the meeting title, description, and available context to generate a relevant result.

You've used Copilot to draft and refine a channel message, summarize a thread, schedule a meeting with Facilitator enabled, and prepare for the session in Outlook — covering the key steps in the pre-meeting workflow.

**End of Lab**