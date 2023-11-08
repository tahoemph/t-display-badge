This comes from https://github.com/Xinyuan-LilyGO/T-Display-S3/tree/main/example/factory  Copyright belongs to Xinyuan-LilyGO as per that Repo.
I made this so it is easier to build an re-flash the factory code.

Some manipulation is needed to make this work.  https://github.com/teastainGit/LilyGO-T-display-S3-setup-and-examples/blob/main/T-DisplayS3_Setup.txt
is a good resource for some boot up.  Also had to define TFT_PARALLEL_8_BIT and undef SMOOTH_FONT in User_Setup_Select.h.  Should revsit why both of
those are needed to be handled in such a hamfisted manner.
