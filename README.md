# Better-ruins
Makes the ruins in the game more powerful
V2.2
Leave a star if you like it. I will appreciate weigthing suggestions.

This fork applies a workaround for a suspected AI unit-swap/ruin side effect in Unciv 4.22.16. Its effect on the reported crash has not been verified.

Only military units can receive the Great General, Great Merchant and Great Artist ruin rewards. Civilian collectors, including the Great Archaeologist, receive other eligible rewards instead. The Great Archaeologist can still construct Ancient ruins three times.

Religious ruin rewards and Faith from City ruins and Historicians only apply when religion is enabled. Turning religion off, including through a Disable religion mod, also removes Pantheon restrictions from the Culture ruin rewards. Other effects remain unchanged, and disabled Faith is not converted to another yield.

Back up your game save and existing mod before installing. Use [this branch URL](https://github.com/Momo630/Better-ruins/tree/fix-religion-disabled-effects) in Unciv's mod downloader for the combined military reward and religion patch; `main` currently includes only the military reward workaround. For updates, reinstall from the same branch URL, as the normal Update action may fetch `main`. Keep the in-game mod name **Better ruins** (`Better-ruins` is the repository name).
