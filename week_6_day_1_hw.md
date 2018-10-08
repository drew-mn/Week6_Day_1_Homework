Episode 1: The murderer is Miss Scarlet.

Episode 2: Function will not work as const 'murderer' cannot be changed or reassigned once declared.

Episode 3: First Verdict:  The murderer is Mrs. Peacock. Second Verdict:  The murderer is Professor Plum.
           First: Murderer is changed to Mrs Peacock as it's a let variable.
           Second: Murder = Professor Plum is a global variable and visible outwith function.

Episode 4: The suspects are Miss Scarlet, Professor Plum, Colonel Mustard.
           Suspect three is Mrs. Peacock

           Suspect three overwritten to Colonel Mustard.
           In isolation suspect three is call as original which is Mrs Peacock.

Episode 5: The weapon is the Revolver. Overwritten from candle stick.

Episode 6: The murderer is Mrs. White.
           plotTwist is the final function called within changeMurderer function, therefore Mrs White is the murderer.

Episode 7: The murderer is Mr Green.  

Episode 8: The weapon is candle stick
           plotTwist changes murderer to Colonel Mustard. In unexpectedOutcome scenario.murderer === murderer is now true which changes weapon to candle stick.

Episode 9: The murderer is Professor Plum.
           If statement 'let murderer = 'Mrs. Peacock'; not called so murderer is Professor Plum.
