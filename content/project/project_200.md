{
  "Title": "PyNets",
  "issue_number": 200,
  "link_to_issue": "https://github.com/ohbm/hackathon2020/issues/200",
  "labels": [
    {
      "name": "Americas hub",
      "description": "",
      "color": "ffaac8"
    },
    {
      "name": "BIDS",
      "description": "some knowledge of BIDS required",
      "color": "562caa"
    },
    {
      "name": "Email ok",
      "description": "",
      "color": "bfdadc"
    },
    {
      "name": "FSL",
      "description": "some knowledge of FSL required",
      "color": "bfa0e8"
    },
    {
      "name": "Hackathon project",
      "description": "use this tag for submitted projects",
      "color": "fcffbc"
    },
    {
      "name": "Jupyter notebooks",
      "description": "Open document format, web-based interactive computing",
      "color": "ef8c62"
    },
    {
      "name": "connectome",
      "description": "connectome computation and analysis",
      "color": "305c99"
    },
    {
      "name": "dipy",
      "description": "",
      "color": "ad86e8"
    },
    {
      "name": "html / css",
      "description": "",
      "color": "c5def5"
    },
    {
      "name": "javascript",
      "description": "some knowledge of javascript required",
      "color": "efe67c"
    },
    {
      "name": "nipype",
      "description": "some knowledge of nipype required",
      "color": "f433db"
    }
  ],
  "content": "## Project info\r\n**Title**:\r\n*PyNets*\r\n\r\n**Project lead**:\r\nDerek Pisner / @dPys\r\n\r\n**Timezone**:\r\nUTC\u221206:00\r\n\r\n**Hub**:\r\n<https://github.com/dPys>\r\n\r\n**Description**:\r\nPyNets is a tool for sampling and analyzing varieties of individual structural and functional connectomes. PyNets enables the user to specify any of a variety of methodological choices  impacting node and/or edge definition, and then sample the prescribed connectome estimates in a massively parallel framework that is conducive to predictive optimization (i.e. grid-search). PyNets is a post-processing workflow, which means that it can be run on virtually any preprocessed fMRI or dMRI data. It relies on Dipy, Nilearn, Networkx, and the Nipype workflow engine under-the-hood. It can now also be deployed as a BIDS application, where it takes BIDS derivatives and makes BIDS derivatives. \r\n\r\n**Link to project**:\r\n<https://github.com/dPys/PyNets>\r\n\r\n**Mattermost handle**:\r\n@dPys\r\n\r\n**Goals for the OHBM Brainhack**\r\n- This project is being included as a BrainHack project in preparation for its 1.0.0 official release before the end of June! I will be working on pushing integration testing and documentation/tutorials primarily throughout the week, but am very open working on any number of sub-project ideas as well (see below for examples).\r\n\r\n- Recruit new developers and co-authors, ensure all possible workflow combinations are bug-proof, and promote the technology more widely to researchers and students in the network neuroscience community.\r\n\r\n**Good first issues**:\r\n- Create a general-purpose function for robustly normalizing any atlas to a given brain template (without requiring the install of an additional dependency)\r\n- Jupyter notebooks with examples running the bids API with your own personal BIDS datasets. \r\n- Browser-based visualization fine-tuning (background with html/css/javascript preferred).\r\n- Unit tests!\r\n- Complete citation.py bibTex entries from docstring and configure duecredit decorators.\r\n\r\n**Good advanced issues**:\r\n- Multiplex graph theory / multigraph community detection.\r\n- Connectome topic modeling (I have a WIP that uses NiMare/Neurosynth and NLP that you can expand upon).\r\n- Converting FSL-based linear and non-linear registration wrappers to pure dipy (I have all the functions that you'd need).\r\n- Port any relevant utilities / general-purpose functions to Nilearn and Dipy wherever appropriate.\r\n- Re-wrap with Pydra.\r\n\r\n**Skills**:\r\nAll skill levels, backgrounds, and perspectives welcome.\r\n\r\n**Chat channel**:\r\n- hbmhack-pynets\r\n<https://mattermost.brainhack.org/brainhack/channels/hbmhack-pynets>\r\n\r\n**Video channel**:\r\nMeetings will be conducted through jitsi. Keep an eye on the mattermost channel for updates.\r\n\r\n**Image for the OHBM brainhack website**\r\n<img width=\"724\" alt=\"Screen Shot 2020-06-13 at 9 05 46 PM\" src=\"https://user-images.githubusercontent.com/16432683/84585219-1af21980-add3-11ea-8969-9fc89c71bb2e.png\">\r\n\r\n**Credit and Onboarding**\r\nA single PR is sufficient to be included on the contributors list. More extensive or regular contributions and collaboration will result in co-authorship on the manuscript in progress.\r\n\r\nSee [CONTRIBUTING]<https://github.com/dPys/PyNets/blob/master/CONTRIBUTING.rst> for more detailed contributing guidelines.\r\n\r\n## Project submission\r\n## Submission checklist\r\n*Once the issue is submitted, please check items in this list as you add under 'Additional project info'*\r\n\r\nPlease include the following above (all required):\r\n-   [x] Link to your project: could be a code repository, a shared document, etc. See [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#link-to-project)\r\n-   [x] Include your [Mattermost handle](https://mattermost.brainhack.org/) (i.e. your username). If you do not have an account, please [sign up here](https://mattermost.brainhack.org/signup_email).\r\n-   [x] Goals for the OHBM Brainhack: describe what you want to achieve during this brainhack. See [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#goals).\r\n-   [x] Flesh out at least 2 \"good first issues\": those are tasks that do not require any prior knowledge about your project, could be defined as issues in a GitHub repository, or in a shared document, cf [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#onboarding-2-good-first-issues).\r\n-   [x] Skills: list skills that would be particularly suitable for your project. We ask you to include at least one non-coding skill, cf. [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#onboarding-skills).\r\n-   [x] Chat channel: A link to a chat channel that will be used during the OHBM Brainhack. This can be an existing channel or a new one. We recommend using the [Brainhack space on mattermost](https://mattermost.brainhack.org/), cf. [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#chat).\r\n-   [x] Video channel: Please create a video channel that will be used during the OHBM Brainhack and share it in your chat channel above. This can be an existing channel or a new one. For instance a [jitsi meet](https://meet.jit.si/) room, cf. [here](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#video-calls).\r\n-   [x] Provide an image of your project for the OHBM brainhack website\r\nWe would like to think about how you will credit and onboard new members to your project. We recommend reading references from [this section](https://github.com/ohbm/hackathon2020/blob/master/.github/ISSUE_TEMPLATE/handbooks/projects.md#credit-and-onboarding). If you'd like to share your thoughts with future project participants, you can include information about (recommended):\r\n-   [x] Specify how will you acknowledge contributions (e.g. listing members on a contributing page).\r\n-   [x] Provide links to onboarding documents if you have some.\r\n"
}