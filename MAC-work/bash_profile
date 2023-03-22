
# ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
# Set Environment
# ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   set -o vi
## Add color to terminal
## from http://osxdaily.com/2012/02/21/add-color-to-the-terminal-in-mac-os-x/
   export CLICOLOR=1
   export LSCOLORS=GxFxCxDxBxegedabagaced
## Set Paths
# ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   export PATH="$PATH;/usr/local/bin"
## iTERM setup tab title
# ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   function title {
	if [ "$1" ] ;
	then
	   unset PROMPT_COMMAND
	   echo -ne "\033]0;${*}\007"
	else
	   export PROMPT_COMMAND='echo -ne "\033]0;${PWD/#$HOME/~}\007"'
	fi
   }
   title

# Quick commands
# ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
   alias BR=". ~/.bash_profile"
   alias la='ls -la'
   alias moer=more
   alias RLoad="source .bash_profile"
   alias tmuxsession="tmux -CC attach"	# Start tmux session
   alias myip='curl ip.appspot.com'
   alias netCons='lsof -i'
   alias flushDNS='dscacheutil -flushcache'
   alias showBlocked='sudo ipfw list'
   alias Tmux='tmux -CC'
   alias viprofile='vim /Users/lewl1/.bash_profile'
   alias cd..='cd ../'					# Go back 1 directory level (for fast typers)
   alias ..='cd ../'					# Go back 1 directory level
   alias ...='cd ../../'				# Go back 2 directory levels
   alias .3='cd ../../../'				# Go back 3 directory levels
   alias .4='cd ../../../../'				# Go back 4 directory levels
   alias .5='cd ../../../../../'			# Go back 5 directory levels
   alias .6='cd ../../../../../../'			# Go back 6 directory levels
   alias show_options='shopt'				#Show_Options; display bash option settings
#   screensaverDesktop: Run a screensaver on the Desktop
#  -----------------------------------------------------------------------------------
   alias screensaverDesktop='/System/Library/Frameworks/ScreenSaver.framework/Resources/ScreenSaverEngine.app/Contents/MacOS/ScreenSaverEngine -background'



# SSH to hosts
# ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
alias ssh-boundless='ssh boundless.eng.pivotal.io'		#SC2 -VM dca10-etl
alias ssh-boundless='ssh boundless.nasa.pivotal.io'		#SC2 -VM dca10-etl
###########################
### PEZ			###
###########################
alias ssh-pezcorkCsw01='ssh llew@10.91.10.29'			#PEZ -Cork core SAN-1
alias ssh-pezcorkCsw02='ssh llew@10.91.10.30'			#PEZ -Cork core SAN-2
alias ssh-pezcorkDsw11='ssh llew@10.91.10.22'			#PEZ -Cork HP Chassis SAN-1
alias ssh-pezcorkDsw12='ssh llew@10.91.10.23'			#PEZ -Cork HP Chassis SAN-2
alias ssh-pezcorkDsw21='ssh llew@10.91.10.14'			#PEZ -Cork destrib Rack02 SAN-1
alias ssh-pezcorkDsw22='ssh llew@10.91.10.15'			#PEZ -Cork destrib Rack02 SAN-2
alias ssh-pezcorkDsw41='ssh llew@10.91.10.11'			#PEZ -Cork destrib Rack04 SAN-1
alias ssh-pezcorkDsw42='ssh llew@10.91.10.12'			#PEZ -Cork destrib Rack04 SAN-2
alias ssh-pezcorkDsw61='ssh llew@10.91.10.27'			#PEZ -Cork destrib Rack06 SAN-1
alias ssh-pezcorkDsw62='ssh llew@10.91.10.28'			#PEZ -Cork destrib Rack06 SAN-2
alias ssh-pezcorkVNX01-cs0='ssh lewl1@10.20.214.104'		#PEZ -Cork VNX01
alias ssh-pezcorkVNX01-spa='ssh lewl1@10.20.214.107'		#PEZ -Cork VNX01
alias ssh-pezcorkVNX01-spb='ssh lewl1@10.20.214.108'		#PEZ -Cork VNX01
alias ssh-pezcorkVNX02-spa='ssh lewl1@10.91.10.101'		#PEZ -Cork VNX02
alias ssh-pezcorkVNX02-spb='ssh lewl1@10.91.10.102'		#PEZ -Cork VNX02
alias ssh-pezsc2-sw-a206-02='ssh llew@10.193.11.17'		#PEZ -SC2 Brocade 8000
alias ssh-pezsc2-sw-a206-04='ssh llew@10.193.11.18'		#PEZ -SC2 Brocade 8000
alias ssh-pezsc2-vnx01-spa='ssh lewl1@10.193.10.38'		#PEZ -SC2 vnx01
alias ssh-pezsc2-vnx01-spb='ssh lewl1@10.193.10.39'		#PEZ -SC2 vnx01
alias ssh-pezsc2-vdx='ssh llew@10.193.11.8'			#PEZ -SC2 VDX Storage Cluster
alias ssh-pezsc2-dd1='ssh lewl1@10.193.2.56'			#PEZ -SC2 DD880
alias ssh-dca1m='ssh root@dca1-mdw1.eng.pivotal.io'		#SC2 -dca1-mdw
alias ssh-dca1s='ssh root@dca1-smdw1.eng.pivotal.io'		#SC2 -dca1-smdw
alias ssh-dca08m='ssh root@dca08-mdw1.eng.pivotal.io'		#SC2 -dca08-mdw
alias ssh-dca08s='ssh root@dca08-smdw1.eng.pivotal.io'		#SC2 -dca08-smdw
#alias ssh-dca10m='ssh root@dca10-mdw1.eng.pivotal.io'		#SC2 -dca10-mdw
#alias ssh-dca10s='ssh root@dca10-smdw1.eng.pivotal.io'		#SC2 -dca10-smdw
alias ssh-dca10m='ssh root@10.193.61.21'		#SC2 -dca10-mdw
alias ssh-dca10s='ssh root@10.193.61.22'		#SC2 -dca10-smdw
alias ssh-dca13m='ssh root@dca13-mdw1.eng.pivotal.io'		#SC2 -dca13-mdw
alias ssh-dca13s='ssh root@dca13-smdw1.eng.pivotal.io'		#SC2 -dca13-smdw
alias ssh-dca17m='ssh root@dca17-mdw1.eng.pivotal.io'		#SC2 -dca17-mdw
alias ssh-dca17s='ssh root@dca17-smdw1.eng.pivotal.io'		#SC2 -dca17-smdw
alias ssh-dd1='ssh dd1.ops.eng.pivotal.io'			#SC2 -TechOPS DD
alias ssh-dd1r='ssh dd1-r.ops.eng.pivotal.io'			#SC2 -TechOPS DD-remote
alias ssh-dd1eng='ssh dd1.eng.pivotal.io'			#SC2 -Data DD-remote
alias ssh-dd2='ssh dd2.ops.dh.greenplum.com'			#DCoE -TechOPS DD
alias ssh-dd2r='ssh dd2-r.ops.dh.greenplum.com'			#DCoE -TechOPS DD-remote
alias ssh-dd2eng='ssh dd2.eng.pivotal.io'
alias ssh-dd3='ssh dd3.ops.dh.greenplum.com'
alias ssh-dd3r='ssh dd3-r.ops.dh.greenplum.com'
alias ssh-dcim='ssh dcim.ops.eng.pivotal.io'			#SC2:VM -TechOPS
alias ssh-dhnfs='ssh dhnfs.ops.dh.greenplum.com'
alias ssh-eagle3='ssh eagle3.pa.greenplum.com'			#PAO -Repo
alias ssh-elcid-p1='ssh root@elcid-prod1.eng.pivotal.io'	#SC2:ElCid -Prod
alias ssh-elcid-p2='ssh root@elcid-prod2.eng.pivotal.io'	#SC2:ElCid -Prod
alias ssh-elcid-p3='ssh root@elcid-prod3.eng.pivotal.io'	#SC2:ElCid -Prod
alias ssh-elcid-p4='ssh root@elcid-prod4.eng.pivotal.io'	#SC2:ElCid -Prod
alias ssh-elcid-p5='ssh root@elcid-prod5.eng.pivotal.io'	#SC2:ElCid -Prod
alias ssh-elcid-p6='ssh root@elcid-prod6.eng.pivotal.io'	#SC2:ElCid -Prod
alias ssh-elcid-st1='ssh root@elcid-stg01.eng.pivotal.io'	#SC2:ElCid -Staging
alias ssh-elcid-st2='ssh root@elcid-stg02.eng.pivotal.io'	#SC2:ElCid -Staging
alias ssh-elcid-sw1='ssh admin@10.194.0.76'			#SC2:ElCid -Brocade Switch
alias ssh-gpdb2='ssh root@gpdb2.eng.pivotal.io'
alias ssh-gpdb3='ssh root@gpdb3.eng.pivotal.io'
alias ssh-gpdb4='ssh root@gpdb4.eng.pivotal.io'
alias ssh-gpdb5='ssh root@gpdb5.eng.pivotal.io'
alias ssh-gpdb7='ssh root@gpdb7.eng.pivotal.io'
alias ssh-gpdb9='ssh root@gpdb9.eng.pivotal.io'
alias ssh-gpdb11='ssh root@gpdb11.eng.pivotal.io'
alias ssh-gpdb12='ssh root@gpdb12.eng.pivotal.io'
alias ssh-gpdb13='ssh root@gpdb13.eng.pivotal.io'
alias ssh-gpdb14='ssh root@gpdb14.eng.pivotal.io'
alias ssh-gpdb15='ssh root@gpdb15.eng.pivotal.io'
alias ssh-gpdb16='ssh root@gpdb16.eng.pivotal.io'
alias ssh-gpdb39='ssh root@gpdb39.eng.pivotal.io'
alias ssh-hdp1m='ssh root@hdp1-mdw1.eng.pivotal.io'
alias ssh-hdp1s='ssh root@hdp1-smdw1.eng.pivotal.io'
alias ssh-nfs1='ssh nfs1.dh.greenplum.com'
alias ssh-nis0='ssh nis0.ops.dh.greenplum.com'
alias ssh-ns0='ssh root@ns0.greenplum.com'
alias ssh-ns3='ssh root@ns3.greenplum.com'
alias ssh-ns4='ssh root@ns4.greenplum.com'
alias ssh-nwr='ssh nwr.ops.pa.greenplum.com'
#alias ssh-nwr1='ssh root@nwr1.ops.pa.greenplum.com'
alias ssh-nwr1='ssh nwr1.ops.pa.greenplum.com'
alias ssh-nwr2='ssh nwr2.ops.dh.greenplum.com'
alias ssh-nwr3='ssh nwr3.ops.dh.pivotal.io'
alias ssh-nwr3sn1='ssh nwr3-sn1.ops.dh.pivotal.io'
alias ssh-nwr3t='ssh root@10.68.168.135'
alias ssh-pxe='ssh 10.194.10.115'				#SC2:TechOPS -PXE Server
alias ssh-sclcon=' ssh scl-con-serial1.ops.pivotal.io'		#SC2:TechOPS -Serial Console
alias ssh-scl5k='ssh admin@scl5k-b117-sw01.eng.pivotal.io'	#SC2:TechOPS -Core Switch
#alias ssh-sclb113='ssh Admin@scl-b113-sw01.eng.pivotal.io'	#SC2:TechOPS
alias ssh-sclb113='ssh admin@10.194.0.6'			#SC2:TechOPS
alias ssh-sclb216sw2='ssh admin@10.194.0.4'			#SC2:TechOPS -PEZ/DataLake switch
alias ssh-sclb216r21='ssh lewl1@10.194.0.5'			#SC2:TechOPS -AppFAB Switch
alias ssh-sclesx-sw1='ssh admin@10.194.0.7'			#SC2:TechOPS -ESX switch
alias ssh-sclesx-sw2='ssh admin@10.194.0.8'			#SC2:TechOPS -ESX switch
alias ssh-sclesx1='ssh root@scl-esx01.ops.eng.pivotal.io'	#SC2:TechOPS -ESX
alias ssh-sclesx2='ssh root@scl-esx02.ops.eng.pivotal.io'	#SC2:TechOPS -ESX
alias ssh-sclesx3='ssh root@scl-esx03.ops.eng.pivotal.io'	#SC2:TechOPS -ESX
alias ssh-sclesx4='ssh root@scl-esx04.ops.eng.pivotal.io'	#SC2:TechOPS -ESX
alias ssh-vc-dev='ssh root@vc-dev-psc-01.core.pao.pez.pivotal.io'
alias ssh-vnx1='ssh vnx1-cs0.ops.pa.greenplum.com'
alias ssh-vnx2='ssh vnx2-spa.ops.dh.pivotal.io'
alias ssh-vnx3='ssh vnx3-spa.ops.pa.greenplum.com'
alias ssh-vnx4='ssh vnx4-spa.ops.pa.greenplum.com'
alias ssh-watcher='ssh 10.194.10.60'				#SC2:VM -TechOPS
###########################
### Appfabric		###
###########################
alias ssh-cs2960-sw1='ssh 10.194.3.142'
alias ssh-cs2960-sw2='ssh 10.194.3.143'
alias ssh-vnxaf='ssh root@vnx5700-spa.af.dh.pivotal.io'
alias ssh-c7k2-bc1='ssh root@10.194.3.120'
alias ssh-c7k2-bc2='ssh root@10.194.3.121'
alias ssh-c7k3-bc1='ssh -oKexAlgorithms=diffie-hellman-group1-sha1 admin@10.194.3.124'
alias ssh-c7k3-bc2='ssh -oKexAlgorithms=diffie-hellman-group1-sha1 admin@10.194.3.125'
alias ssh-c7k4-bc1='ssh root@10.194.3.128'
alias ssh-c7k4-bc2='ssh root@10.194.3.129'
alias ssh-c7k5-bc1='ssh root@10.194.3.132'
alias ssh-c7k5-bc2='ssh root@10.194.3.133'
alias ssh-c7k6-bc1='ssh -oKexAlgorithms=diffie-hellman-group1-sha1 root@10.194.3.136'
alias ssh-c7k6-bc2='ssh -oKexAlgorithms=diffie-hellman-group1-sha1 root@10.194.3.137'
alias ssh-c7k6-sw1='ssh admin@10.194.3.134'
alias ssh-c7k6-sw2='ssh admin@10.194.3.135'
alias ssh-c7k7-bc1='ssh root@10.194.3.140'
alias ssh-c7k7-bc2='ssh root@10.194.3.141'
alias ssh-br5100-sw1='ssh -oKexAlgorithms=diffie-hellman-group1-sha1 admin@10.194.3.144'
alias ssh-br5100-sw2='ssh -oKexAlgorithms=diffie-hellman-group1-sha1 admin@10.194.3.145'


# Setting PATH for Python 3.5
# The orginal version is saved in .bash_profile.pysave
# ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
PATH="/Library/Frameworks/Python.framework/Versions/3.5/bin:${PATH}"
export PATH


test -e "${HOME}/.iterm2_shell_integration.bash" && source "${HOME}/.iterm2_shell_integration.bash"
