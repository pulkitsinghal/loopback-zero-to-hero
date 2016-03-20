|||info
# info

You may skip this section, it is not directly related to learning LoopBack, its purely for the super curious.
|||

### How to provide feedback?

- Issues can be reported here:
https://github.com/pulkitsinghal/loopback-zero-to-hero/issues
- Conversations and discussions should be directed to the gitter chat room: https://gitter.im/pulkitsinghal/loopback-zero-to-hero

### How was this VM prepared for training?

- Base Stack: `CODIO-CERTIFIED / Node.JS + nvm`

- Current/Default Node Version: `v0.10.43`
  - How it was setup:
    ```
    $ nvm install v0.10.43
    $ nvm alias default 0.10.43
    ```
  - To check the version in this VM now, try:  `nvm ls`
    ```
    $ nvm ls
    v0.10.43
    v0.12.0
    current: v0.10.43
    default -> 0.10.43 (-> v0.10.43)
    ```

- Installed strongloop's command-line-utility (CLI) with: `npm install -g strongloop@6.0.0`
  - The installed CLI can be invoked with `slc`
  - To check the version try: `slc version`
    ```
    $ slc version
    strongloop v6.0.0 (node v0.10.39)
    ├── strong-arc@1.8.8 (fb756f2)
    ├── strong-build@2.1.0 (47dd24a)
    ├── strong-deploy@3.1.2 (be6180a)
    ├── strong-mesh-models@8.1.0 (62e539b)
    ├── strong-pm@5.2.0 (4197516)
    ├── strong-registry@1.1.5 (f46e58f)
    ├── strong-start@1.3.2 (1327018)
    ├─┬ strong-supervisor@3.3.1 (1e39220)
    │ └── strong-agent@2.0.2 (4ea7ee9)
    ├── generator-loopback@1.20.3 (9160167)
    ├── node-inspector@0.7.4
    └── nodefly-register@0.3.3
    ```

- Installed a utility known as `tree` via `Tools > Install Software`

  ```
  Install log for: tree
  => Extracting archive...
  => Installing...
  => Activating...
  => Installed tree 1.7.0
  ```
