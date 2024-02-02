# MDE Linux Command Flow chart in Mermaid live format

```
flowchart TB
    mdatp --> config
    config--> mdatp_config
    mdatp_config["
    cloud
		cloud—diagnostic
		real—time—protection
		real—time—protection—statistics
		collect—scanned—files—per—process
		cloud—automatic—sample—submission
		passive—mode
		behavior—monitoring
		behavior—monitoring—statistics
		proxy
		ebpf—supplementary—event—provider
		ptrace—scope
		manage—boot—record
		network—protection
		automatic—definitions—update
		maximum—on—demand—scan—threads
		scan—after—definition—update
		scan—archives
		log—rotation—parameters
		enable—file—hash—computation
		schedule—quick—scan
		schedule—weekly—scan
		scheduled—scan—settings
    "]

    mdatp --> connectivity
    connectivity --> test

    mdatp --> definitions
    definitions --> deflist
    deflist["
        update
		path
		restore
    "]
    

    mdatp --> diagnostic
    diagnostic --> diglist
    diglist["
        antivirus—engine—pool—content
		create
		real—time—protection—statistics
		event—provider—statistics
		behavior—monitoring—statistics
		hot—event—sources
		ebpf—statistics
		upload
    "]

    mdatp --> edr
    edr --> edrlist
    edrlist["early—preview
		group—ids
		tag
		exclusion"]
    
    mdatp --> exclusion
    exclusion --> exclist
    exclist["extension
		file
		folder
		list
		process"]
    
    mdatp --> health
    health --> output_BUT_START_HERE

    mdatp --> help
    help --> output

    mdatp --> log
    log --> loglist
    loglist["
    level
    view"]
    
    mdatp --> notice
    notice --> output

    mdatp --> scan
    scan --> scanlist
    scanlist["
    cancel
		custom
		full
		quick
		list
    "]

    mdatp --> network_protection
    network_protection --> netlist
    netlist["
    exclusion
		trace
		feature—control
		set—log—level
		remote—settings—override
		reset"]
    
    mdatp --> threat
    threat --> threatlist
    threatlist["allowed
		get
		list
		policy
		quarantine"]
 
    mdatp --> version
    version --> output
    
```
