# runner-pickup-probe

The GitHub-hosted half of a runner pickup latency comparison. One do-nothing job,
dispatched with a chosen `runs-on` label and a chosen number of jobs at once, so
`started_at` minus `created_at` is how long a job waited for a runner.

It is public because standard GitHub-hosted runners are free for public
repositories. It runs no code beyond `echo`.
