# Sample Python Application for `piku`

This is a simple Python app that demonstrates:

- HTTP port selection via the `PORT` variable (set in `ENV`)
* An independent worker process (that is auto-restarted upon exit) 
* Another independent worker with a built-in scheduler

To publish this app to `piku`, clone the repository and run the following commands:

```bash
git remote add piku piku@your_server:sample_python_app
git add .
git commit -a -m "initial commit"
git push piku master
```
