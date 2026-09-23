### Fix my PR skill

  1. read each comment, skipping resolved comments
  2. for each one, spawn a worktree-isolated subagent and run them in parralel
  3. fix one comment per commit, but do not push
  4. at the end, push, and write a one line summary of each comment/commit for me to reply
  5. you do not reply to comments yourself
  6. when you have pushed, monitor the PR's build job, if it fails, debug and create a new commit fixing the issue, then push, summarise, and monitor until done
