from setuptools import setup, find_packages

setup(
       name='customenv',
       version='0.1.0',  # Choose your version number
       packages=find_packages(content/BenchMARL/benchmarl/conf/task),
       package_data={'customenv': ['*.yaml']},  # Include YAML files
       install_requires=[
		'pyyaml>=5.4.1','benchmarl' ],
   )
