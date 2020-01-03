EvELYN : EVidence Evaluation, Linking, analYsis, Notetaking tool

What is this for?
    There are lots of pieces of evidence in Phantom Shot Simulation, and many of them have to do with multiple
    "things," which makes organizing hard. For instance, the fact that all the rooms are soundproof... Do you file
    that under North's June 4 log where we learned this, West's Igloo because that's relevant to his murder? My
    solution is to instead have a hierarchy of tags. If you have a clue, give it a tag. You can then select all
    clues that match that tag.
Explain the "tag hierarchy"?
    Some clues are relevant under narrow conditions, while others are relevant under more general conditions, even
    though they're about the same thing. For instance, that the igloos are soundproof matters for all the igloos,
    but if you just want to know about igloos in generals, you probably don't care that East's has potted plants.
    You can select a tag to open. All clues tagged with a tag "more general" in the hierarchy will then open!
How do I open tags?
    Click on the expand/collapse buttons to open the lists of tags that you look for. Click the checkbox to reveal
    all clues marked by that tag, or a tag "more general" in the hierarchy.
Can I add clues?
    Yes! Add clues in the documentation. Begin with a list of tags, separated by semicolons in Courier New.
    Write the rest of the clue after, changing out of Courier New. (If you want something more technical, go look
    at the source code yourself.)
Can I rearrange clues?
    Sure. Please keep clues in "clusters". So anything involving Reds belongs in the Reds section, etc.
Can I add new labels?
    Sure. To add a new top-level tag, type the tag at the start of the document. To add a new tag that's a
    subcategory of something else, use the syntax `OLD TAG: NEW TAG`. Tabbing is nice but not necessary.
    Enthalpy will correct it if you make a bad change. Please get opinions from chat if you're making a large
    reorganization.
Can I add a new category of tag, like "Thoughts" or "Red"?
    Suggest it to Enthalpy. That requires modifying the EvELYN code.
I broke the site! Can you fix it?
    Yes, just let me know. I'll then publish an altered version of EvELYN where you can't break it so easily.
    That said, if it looks broken, open up the developer console and see if there's a message printed there.
    If so, that should tell you what went wrong.

TODO:
* The current version breaks if it detects an unrecognized tag. Add a new unsorted category, ASAP.
* Include the PSS logo
* Include an "emote" to distinguish between narrative clues, RUNE clues, Blackrune clues, Isa's updates, reds, and
  theories. It would automatically be added before each clue.
  * Narrative = Magnifying glass
  * RUNE = Computer
  * Blackrune = Blackrune's CoB avatar (Yuuka Kazami from Touhou)
  * Isa = ?
  * Red = :red:
  * Theories = ?
