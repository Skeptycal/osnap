Notes on the roadmaps session at the 2018 NumFOCUS Summit

Presentation on NumPy roadmap: https://www.slideshare.net/RalfGommers/numfocussummit2018roadmapssession

Discussion: should there be dates on a roadmap?
Consensus that if a project has only volunteers, a roadmap should not (cannot) have dates.
Companies and funding bodies often look for dates when deciding on whether or not to fund something.
Mention of ZeroMQ example - they did have dates, missed them, had a backlash. There is a detailed write-up by one of the maintainers somewhere.
For when there is funded work: opinions still vary on if and how to publish dates on a roadmap.
Suggestion to let contributing entities (e.g. devs paid by companies) be responsible for dates/deadlines if they want to do that.
Suggestion to keep dates internal (however, many projects don’t have an “internal” …)

Breakout groups

Notes Adrian/Sylvain/Ralf: https://hackmd.io/v-UPQDZCRs6JQocmPfinIg#


# NumPy

NumPy 3-5 year funding, work on:

- numpy.org & ecosystem websites (2 MM + $40k)
- interoperability protocols (1-2 MY)
  - sparse matrices
  - distributed arrays
  - GPU-arrays
- sustained positive balance of merged vs open PRs and closed vs opened issues (1 MY/yr on top of volunteer effort)
- Community liaison for NumPy with rest of the ecosystem (0.5-1 FTE, ongoing)

Major work: >= 6 person months

Personas:

- developers of downstream packages
- first-time or occasional contributors
- people learning to work with Python and numerical data
- all kinds of personas
- docs: advanced users / C API users
- packagers
- funders?
- ...

#  Jupyter

- What would your project want to work on for 3-5 years

  Jupyter
    - """dashboarding""" with kernel backend support (voila)
    - debugging support
    - data source abstraction for "static" kernel-less notebooks.
  Cling (C++ interpreter) & Xtensor (C++ dataframe and N-D array)
    - allow re-defining functions, types
    - expand, promulgate beyond CERN.
    - fully fledged C++ dataframe.
    - Support a new Python ducked type numpy-style array - "depends" on current NEP and acceptance by other project.

- Time frame
    - dashboarding: ongoing 1-year effort
    - debugging: 1Y FTE for protocol and python reference implementation
  
# AstroPy
  
  Major work areas:
  
  - General performance enhancements (*3–6 months*)
  - Maintenance (*indefinitely*): GitHub issue and pull request management / labeling, monitoring CI, documentation build
  - Explore merging astropy.units with unyt (*1–2 months*)
  - More complete benchmarking and better assessment of performance changes with code changes (*6 months*)
  - More comprehensive educational materials and maintenance of documentation, tutorials, guides (learn Astropy) (*12 months*)

