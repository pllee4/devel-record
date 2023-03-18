# 18/03

## Update
- Automate [workflow](https://github.com/pllee4/docker/blob/master/.github/workflows/build.yml) for building and pushing of docker image in weekly basis
- This is motivated by sudden failure in usage of conan package due to new release of conan 2.0.
- The algorithm repo has also been updated with [reusable workflow](https://github.com/pllee4/algorithm/commit/2e1c17a34ecbddddf3544fab3601739012b8d546) which would check building and creation of package in weekly basis.
- As gitlab has not yet supported conan 2.0 for package registry at the moment, the workflow would help in detecting possible changes in conan 2.0 that is just released and not yet stable enough.
- Automated building and checking in weekly routine shall be helpful in identifying any update of tools or package needed in repository.