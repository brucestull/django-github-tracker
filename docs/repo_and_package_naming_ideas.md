# Django Package Naming

- [Django Package Naming - ChatGPT - Private](https://chatgpt.com/g/g-p-6957cd1d048081919036fef59736594f-github-repository-django-project/c/695a4cb0-7298-832d-9642-17d2e1dbb0e0)

Here are a few solid naming options that fit “a Django app/package you can pip-install and plug into your Personal Assistant” (and won’t paint you into a corner later).

## 1) GitHub repository name (pick one)

**Top recommendation (clear + flexible):**

* `django-github-tracker`
  *Reads well, obvious purpose, doesn’t imply it’s only “repos” (you may add issues/PRs/projects later).*

**Also good:**

* `django-github-inventory` (nice if your PA tracks “assets” broadly)
* `django-github-dashboard` (best if it’s more UI/reporting oriented)
* `django-github-repo-tracker` (more specific, slightly narrower)

## 2) PyPI package name (pick one)

**Top recommendation (common Django package convention):**

* `django-github-tracker`

**If that name is taken on PyPI, good fallbacks:**

* `django-github-tracker-app`
* `django-github-repo-tracker`
* `django-github-inventory`

### Quick naming tip (so install + import feel clean)

* Repo can be `django-github-tracker`
* PyPI can be the same
* Django app label inside the package could be something like `github_tracker` (underscored, short)

If you tell me whether you want this to be mostly **models + admin** vs a full **pluggable app (urls/views/templates/api)**, I’ll narrow it to the best “forever name” from the list.
