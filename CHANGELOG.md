# 1.0.1 (12/04/2017)

- adds timestamp to all logs
  - adds the ability to toggle them on and off

# 1.0.0 (11/29/2017)

- fixes pipeline to find times recursively
  - cleans up duplicate code
- handles if git is not present
- removes the dependency on having a package.json to get name and description
- removes the qs module uses native querystring
- cleans up stages markup to have the title inlined
- adds report tab to show report in JSON
- adds times to all pipeline nodes
  - the end now shows a cumulative time
- fixes bug if output is not defined in config
- config is now the pipeline parsed
- adds an `output` flag to the CLI that sets the output of the report
- adds an `browser` flag to CLI that allows setting browser to be configured to be open or not
- abstracts execution logic from binary and tests it separately
- cleans up and rearranges UI
- adds story to storybook stories to reflect a full report view
- removes `babel-minify-webpack-plugin`

# 0.2.9 (11/13/2017)

- adds qs module to dependencies

# 0.2.8 (11/13/2017)

- moves from psychic-ui to psychic.css (reduces bundle from 257 KB -> 239 KB *7%*)
- updates dependencies

# 0.2.7 (10/12/2017)

- adds babel-minify-webpack-plugin which reduces build output from 345K to 263 KB

# 0.2.6 (09/26/2017)

- fixes broken event emitter due to async
- fixes issue with nested runs
- allows the ability to run parts of the pipeline
- updates to react 16.0.0, slims example build output from 898 KB to 343K

# 0.2.5 (09/23/2017)

- adds env config to override process environment variables during build

# 0.2.4 (09/16/2017)

- generates a similar pipeline view in the console

# 0.2.3 (09/13/2017)

- adds arrow to show opened stages
- time indicator on stage is now light grey
- cleans up inlined styles (reduces bundle size)
- updates dependencies

# 0.2.2 (09/01/2017)

- adds react-storybook stories to show use cases
- adds tests for pipeline and utils
- fixes bug with pipelines that does not fail parent if child fails
- abstracts stages and icon classes

# 0.2.1 (08/31/2017)

- package and run as a global binary with pkg

# 0.2.0 (08/31/2017)

- adds a -d, --debug option to control the output of a build.json file that contains information about the build pipeline
- sets the first stage to the default default on page load
- capture the build pipeline config if it exists (display this under a tab named Config)
- fixes a bug with commands being opened due to not using keys
- both the stage icons and the pipeline icons are the same, so are the colors

# 0.1.0 (08/24/2017)

- updates doc page
- UI pipelines are now svgs
- allows nested pipelines
- extends pipelines UI to show nested flows

# 0.0.1 (08/22/2017)

- basic functionality
