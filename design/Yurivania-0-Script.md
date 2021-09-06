# Yurivania 0: Soul Night Prelude
by Paige Ashlynn
version 1.1, August 1, 2021


## 0. Intro

1. Logo / Credits Screen
    🖤 Trans Game Dev Birthday Jam 2021 🖤
    Design, Scenario, Graphics, Code: Paige Ashlynn
    Music: Caidence Stone
    Fonts: Jeremy Odubere, Clint Bellanger
2. Title Screen
    YURIVANIA
    Soul Night Prelude
    _intro_jingle_
    Press Start
    _if_no_game_is_saved_
        Cut to an explanation of controls, then Area: Foothill Path.
    _otherwise_
        Offer to load saved game or begin anew.
        The rest of the script assumes the player is beginning a new game.
3. Opening Narration
    NARRATOR:  Many years ago in the Midnight Palace....


## 1. Area: Foothill Path
    Tibby, a walking skeleton, and Stheno, a masked gorgon, exit the Midnight Palace together.
    
    They are on a tree-lined walk, perhaps an orchad path, leading from the tall
    rough-cut stone of the Palace's exterior to a steep set of ascending steps.
    Beyond the trees a wind of the palaces comes to an abrupt end.
    Above it tall, steep mountains loom against a dark, star-filled sky.

    TIBBY: It's Soul Night at last!  I can't believe it!

    STHENO: Right??  It's always my fave night of the year.

    TIBBY: And this year is special!  We're opening the Palace's first Soul Portal~~
    The community really came together to make this happen!
    Thanks for coming with me, Stheno~!

    STHENO: Of course!  You're my bestie!
    But, what exactly is a Soul Portal?
    It's to help ghosts, right?

    TIBBY: Right.  You see, the realms beyond mortality are myriad, and can get pretty confusing.
    It's easy to get lost.  The Portal is a gateway connecting realms together.
    Any spirits who lose their way can use it to get back on track.

    STHENO: Awesome!  Is the site hard to reach?  I've never been here before.

    TIBBY: Nah, there's a stairway the whole way up.
    But, now that you mention it...  there's bound to be loads of spiritual energy up there tonight.
    That can be disorienting for undead like me.
    I'm going to stick close to you!

    STHENO: Cool by me!  Let's go!

    _PLAY_begins._

    _Party_Talk_
    TIBBY: The mountain is quite steep....  Let's follow the path left and take the stairway.


## 2. Area: Mountain Stair
    Stheno leads Tibby up the stairs to the foot of a massive overhanding cliff.
    There are more trees here, scattered along the stony ground, as well as some outlying Palace buildings.
    A big full moon gleams down from over the crags, lighting up a wide flat space of paving and wild plants.
    From here they can see a long, wide stone staircase cut into the mountainface, switching back and forth as it climbs.
    The two make their way toward these steps.
    
    As they walk below a particularly large tree near the foot of the steps Tibby suddenly grabs Stheno's cloak, halting them.
    Ahead a strange light has appeared.  From somewhere overhead a tall, bright blue flame has flickered into view.
    It hangs in the air without visible fuel or support.
    Swiftly the ghostly light swirls around the paved space at the foot of the mountain, passing right above their heads
    before vanishing from view once again.
    
    Tibby recovers herself and turns to Stheno.
    
    TIBBY: That's the spirit energy I was talking about!
    We'd better keep our eyes open...!

    Stheno silently agrees.
    
    They begin climbing the stairs, but have hardly risen above the level of the outbuildings when an unknown voice rings out above:
    
    GHOST 1, from off screen: Hey!

    Stheno and Tibby look up.  Above them on an outcropping of stone is the rotund yellow-white figure of a phantom.

    GHOST 1: Wow, am I ever glad you two came along!
    I heard a new portal was opening here tonight, so I was on my way to check it out... but, I got lost... and then I got stuck!
    (The ghost displays an embarrassed sweatdrop emote.)

    GHOST 1: Can you help me down?

    STHENO: Of course!

    TIBBY: We're on our way to the Soul Portal ourselves.
    We'd be happy to take you with us!

    GHOST 1: Oh, thank you so much!
    I think there may be others lost on the mountain side....

    STHENO: No worries, we're on the case!

    (The ghost waits for them to climb up, relieved.)

    TIBBY, to Stheno: They're right.  I sense six ghosts lost nearby.

    _PLAY_resumes._

    _Party_Talk_
        _if_ghosts_remain_lost_
            TIBBY: I could be wrong, but... I think there are _number_of_lost_ghosts_ ghosts lost nearby.
        _otherwise_
            TIBBY: I think we found everyone!  Let's head up!

    _On_attempting_to_exit_upward_before_finding_all_lost_ghosts_
    TIBBY: This is the way to the top, but I don't think we've found everyone yet.
    Let's take another look around.

    _On_rescuing_Ghost_1_
    GHOST 1: Thanks so much!  How embarrassing this has been!
    (The ghost displays a grateful heart emote.)

    _On_rescuing_Ghost_2_
    GHOST 2: Wow, you're quite the dare devil!!
    I'm gonna stick with you till we get to the top!
    (The ghost displays a shocked emote.)

    _On_rescuing_Ghost_3_
    GHOST 3: Oh, hi!
    The stars in the mountains are always so beautiful on Soul Night.  I got quite distracted!
    If it's all right, I'll follow you to the summit.
    (The ghost displays a grateful heart emote.)

    _On_rescuing_Ghost_4_
    GHOST 4: Oh, bother.  How did I end up here?
    With all the spirit energy around, I can hardly tell up from down.
    Would you be able to help me?

    STHENO: Absolutely!  We'll take you to the Portal.

    GHOST: Wonderful!
    (The ghost displays a grateful heart emote.)

    _On_rescuing_Ghost_5_
    (The ghost displays a thinking pause emote.)
    GHOST 5: Nope, there's no way up here....
    (Ghost 5 suddenly notices Stheno and Tibby.)
    Oh hey!  Do you know how to get to the summit?

    STHENO: Yep!  In fact, we came to offer you a hand.

    GHOST: Well, aren't you a blessing!  Let's get going!

    _On_rescuing_Ghost_6_
    GHOST 6: Oh, thank goodness!  People!
    I was afraid I'd be stuck here all night!
    I thought these ropes would lead to the top, but they end at this platform.
    Y'all're my heroes for coming out here to save me!
    (The ghost displays a grateful heart emote.)

    _On_finding_all_lost_ghosts_
    TIBBY: That's everyone!  Let's head to the Portal!


## 3. Area: Cliff Face
    Stheno, Tibby, and the ghosts reach a grassy meadow overlooking the cliff's edge
    high up the mountainside.  Behind them the upper peaks can be seen: they have
    almost reached the top.
    
    Beyond this level space the stairs continue upwards; however, there are large
    gaps in the stairs where the stones and soil have washed away, taking the steps
    with them.  A large red oni is standing at the nearest gap, holding some tools.
    
    TIBBY: Suzuka!

    SUZUKA, the oni ranger, turning to greet them: Heya Tibby.  On your way to the ceremony?

    TIBBY: Yes, we were.  But what's going on here?

    SUZUKA: Ah, well.  The stair has fallen, I'm afraid.
    That's soil hydrology for ya.  Thing wasn't built right.
    I'm repairing it.

    (Tibby displays a dismayed shock emote.)

    SUZUKA: But don't worry!  There's another way up.
    Someone named Alraune has been kind enough to grow a set of vines along the cliff face.
    You've just got to climb!

    (Behind the oni, the rockface is covered in long, snaking vines.)

    STHENO: You said Alraune?!

    SUZUKA: That's right.  She's up top already.
    I don't think we've met.  I'm Suzuka, local oni ranger!
    May I ask your name and pronouns?

    STHENO: Oh, uh.  Yeah, sorry!
    I'm Stheno, she/her.  Nice to meet you!

    SUZUKA: I use she/her as well.
    But no time to chat if you all want to make it to the ceremony!
    Just head right on up.

    (Suzuka goes back to her work.)

    (Stheno displays an embarrassed blush emote.)

    TIBBY: Something wrong?

    STHENO: But... these vines are Alraune....
    We'll be, like... climbing on her *body*!

    (Tibby displays an embarrassed sweatdrop emote.)

    TIBBY: Stheno.  I know you have a crush, but really.
    Just, y'know, think of it like a leg up.

    STHENO: Right, of course.  Okay.  A leg up.
    Totally.  Not weird at all.

    (The party climbs up onto the vines and continues upwards.)

    _PLAY_resumes._

    _Party_Talk_
    TIBBY: I remember this place!  We're almost there.

    _On_reaching_Lucy's_ledge_
    LUCY: You're quite adventurous to find me up here.  Let's keep this little moon-drenched shelf between us.


## 4. Area: Summit

    At last our party reaches the summit.  The vines lead up to a rocky dome overlooking the mountains and valleys
    spreading out on all hands.  Above them the night sky stretches black and clear, glittering with a multitude of
    stars.  It seems quite a crowd has assembled here tonight.  Alraune the plantgirl is rooted near the edge
    so that her vines can trail down below.  A tall, slinky vampire woman is standing there also, talking with her.
    
    _PLAY_continues._

    _Party_Talk_
    TIBBY: This is it, the summit!

    _On_reaching_Alraune_

    The company approaches Alraune and the vampire.
    The ghosts, for the moment forgotten, hang back
    on the shadowy edge of the festivities.
    
    (Tibby displays an excited heart emote.)

    (Josette the vampire displays an excited heart emote.)

    JOSETTE: There's my little corpseling~!

    TIBBY: Josette!  Did we make it on time?

    JOSETTE: Yes, you're just in time.
    Baphy's about to say the final incantation.

    TIBBY: Sweet!  I'm so glad we made it.

    (Stheno displays an embarrassed blush emote.)

    (Alraune displays an embarrassed blush emote.)

    (Tibby and Josette join hands and disappear into the crowd, leaving Stheno and Alraune to talk.)

    STHENO: Uh, hey Alraune....

    ALRAUNE: H~, hey Stheno.  Um!  I'm glad you could make it. It's super nice to see you!

    STHENO: Yeah, yeah, totally!  Likewise!
    Thanks for, uh, you know, the help up....

    (Stheno and Alraune both blush again.)

    ALRAUNE: Oh yeah, for sure!

    (There is an awkward pause.)

    (Stheno displays a thinking pause emote.)

    (Alraune displays a thinking pause emote.)

    STHENO: I better catch up with Tibby.
    Um,
    ... ... ...
    See ya!

    (Stheno displays an embarrassed sweatdrop emote.)

    Before Alraune can say anything else, Stheno hurries
    away into the crowd.  All sorts of shapes are visible
    in the darkness ~~ it seems the whole Palace population
    is represented at tonight's ceremony.
    
    Stheno finds Tibby and Josette on the edge of a ring
    of stone blocks from which rise four tall stone pillars.
    Above each pillar a pale flame flickers.  In the center
    Baphomet, the demon elder, is seated, a look of concentration
    on her face.
    
    As the assembly watches Baphomet utters an indecipherable
    incantation.  Immediately there is a bright flash and
    a golden-white portal shines in the air above the stone ring.

    Suddenly the ghosts that Stheno and Tibby helped scale the
    mountain stream in from the periphery, floating over the heads
    of the crowd and vanishing into the light of the Portal.
    
    The crowd gazes upward as they depart for other planes.
    
    The last ghost hesitates a moment, then looks back at
    Stheno and Tibby.

    GHOST 1: Thanks so much, Tibby and Stheno.
    We wouldn't have made it without you.
    See you, one day, on the other side!

    _If_the_player_has_not_collected_sufficient_spirit_energies_
        (Pan upwards away from the crowd and the Portal to show the distant glowing moon.)
        _Cut_to_CLOSING_NARRATION_
    _Otherwise_
        Stheno pauses for a moment, then turns back.
        Stheno retraces her steps back to where Alraune is waiting.

        STHENO, summoning all her courage: Hey, Alraune...
        I really like you!  Would you like to go out sometime?

        (Alraune displays an excited shock emote.)

        ALRAUNE: YES!!
        The truth is... I've been crushing on you for a long time!

        (Stheno displays an excited heart emote.)

        (Alraune displays an excited heart emote.)

        (Pan upwards away from the pair to show the glittering stars.)

## 5. Closing Narration

    NARRATOR:  Thank you for playing!
    You collected _number_of_spirit_energies_ spirit energies tonight!
    Look forward to more adventures in the Midnight Palace~~

## The End
