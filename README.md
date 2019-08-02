WF Demo Extension
=================

## How to use it?

Create your demo WF docker container:

### Create docker image

Create your custom `Dockerfile` in `~/.wf-docker-workflow/Dockerfile`:

```Dockerfile
FROM fchris82/wf

RUN wf/demo-extension
```

Build (there is a `.` in the end of the command!):

```bash
$ wf --rebuild
```

### Check

```bash
$ wizard
```

You have to see the `Demo Extension` wizard.
