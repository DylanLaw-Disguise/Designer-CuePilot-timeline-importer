# Designer-CuePilot-timeline-importer

Import cuepilot notes and camera cuts into the disguise timeline from the CSV exported from cuepilot

This plugin works by importing your timeline from cuepilot into disguise, it does this by exporting as a CSV first from cuepilot, inside the plugin you upload your cvs file and select import to disguise timeline, in cuepilot if the start time is negative, then the importer will hold that in cache as the global offset, meaning if the cuepilot starts at -10 seconds, then in the disguise timeline it will be imported at 0, as we dont do negatives! this statement carries on for the note import as well, this will allow you to select multiple csv files and import them to your timeline that will appear in grouped folders, these grouped folders are named based from the cvs file name and the layers inside are what the note states in cuepilot timeline,

later development currently in developtment going to be a demo disguise file that is synced up to a demo cuepilot project, as you play cuepilot it will play disguise timeline, and as camera cuts are present in cuepilot, it will cut to the cameras in disguise, this is using the MR set with osc indirection that is controled from cuepilot, however curentlty exploring including a osc command layer instead to trigger the changes automatically inside disguise as you scrub accross the timeline!

much later development all of these features have been made from client requests between me(dylan) and ***** from cuepilot, these are non official fixes to customer requests, Use and modify at own risk!

any questions email Dylan.law@disguise.one
