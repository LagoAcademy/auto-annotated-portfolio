---
type: PageLayout
title: Join Us
sections:
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: '"Join Lago Academy – Kickstart Your Football Journey!"'
    subtitle: Unleash Your Potential with Top-Class Training at Lago Academy
    text: >+
      ### **Why Join Lago Academy?** 


      1.  **Expert Coaching:** Learn from seasoned coaches like Donal and
      Valeriy, who bring years of experience in training boys and girls at all
      levels.


      2.  **Competitive Matches:** Gain real-game experience by competing
      against other academies and putting your skills to the test.


      3.  **Team Spirit:** Be part of a supportive community that values
      teamwork, discipline, and sportsmanship.


      4.  **Comprehensive Training:** We offer tailored programs focused on
      skill development, from shooting and defending to agility, tactics, and
      mental strength.


      5.  **All Levels Welcome:** Whether you're a beginner or an advanced
      player, we have programs designed to help you grow.



    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
  - type: ContactSection
    title: Contact Us
    text: I'm look forward to hearing from you.
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: true
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: SelectFormControl
          name: Which Position Do u want to Apply for
          label: Subject
          hideLabel: false
          defaultValue: Please choose...
          options:
            - Attacking
            - Other
          width: full
          isRequired: false
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
---
