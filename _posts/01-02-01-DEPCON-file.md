# The DEPCON file

At the root of the project we will have a DEPCON.yml file where, at least, contains the current DEPCON level:

<pre>
currentLevel: 4
levels:
  0: ZERO
  1: HOUSTON
  2: HURRY
  3: CALM
  4: SPRINT
  5: VERSION
</pre>

Could be interesting that every DEPCON change has a dedidated commit made by the DEPCON level owner and a very clear commit message.

In the future, we can review the history of the project viewing the git log of this file as:

`git log DEPCON.yml`

