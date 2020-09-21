A theme for flickerfusion.com

Because I always screw up how the submodules work.

Check in changes here then push up to gh

Then

```
cd flickerfusion.com/themes/60hz
git checkout main
git pull origin main
```

Then, stage the submodule and commit that:

```
cd ../..
git add themes/60hz
git commit -m "Updating the latest 60hz"
```

Now push flickerfusion.com to gh

```
git push origin main
```
