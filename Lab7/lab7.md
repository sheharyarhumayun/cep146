Exercise 1 Reflection Answers:

1. Why did the conflict occur?
Both branches modified the same lines in the Skills section of portfolio.md differently. Git couldn't decide which version to keep.

2. What lines in the file were changed in both branches?
The Skills section — specifically the - Programming: and - Git: lines, plus new lines each branch added (Web Development vs Database).

3. What would have prevented this conflict?
Pulling the latest changes before editing, coordinating which device edits which file, and merging branches sooner instead of letting them diverge.

4. In real life, how do you avoid conflicts when working on multiple devices?
Run git pull before starting work, git push after each session, commit frequently, and avoid editing the same file offline on two devices at once.

5. Most challenging part + how Git helped?
Deciding which changes to keep from each branch. Git made it easy by inserting clear markers (<<<<<<<, =======, >>>>>>>) showing exactly where the conflict was and which side each change came from.
