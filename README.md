# mptjags

This tool converts MPTinR model descriptions into an equivalent JAGS model. Restrictions on parameters (MPTinR restriction files) are not supported as of now. The JAGS model will assume uniform priors on all parameters. Constraints have to be added manually.

### Usage

To execute the tool, simply provide the model to convert:

```plain
python mptjags.py <mpt.model>
```

Creating new files containing the JAGS model output is possible by redirecting the script's output:

```plain
python mptjags.py <mpt.model> > <output.j>
```