# emacs_config

alias

alias ctags 'mkdir -p $HOME/.emacs-desktop/$CLEARSTART_VIEWTAG && find  /vobs/gsn_rel_gsn/idp /vobs/gsn_rel_ncs/idp /vobs/gsn_rel_sgsn/idp/idp_mps/idl /vobs/gsn_rel_sgsn/idp/idp_mts/idl /vobs/gsn_rel_sgsnw/idp/idp_ups/idl /vobs/gsn_rel_sgsne/idp/idp_eps/idl -type f -name "*.[eh]rl" | sort | xargs etags -a --language=erlang --output=$HOME/.emacs-desktop/$CLEARSTART_VIEWTAG/TAGS'
alias dtags 'rm -rf $HOME/.emacs-desktop/$CLEARSTART_VIEWTAG/TAGS'

alias cptags 'mkdir -p $HOME/.emacs-desktop/$CLEARSTART_VIEWTAG/platform && find ${GSN_WS_ROOT}/sgsn_mme/capella/ncs /vobs/gsn_rel_gsn/idp /vobs/gsn_rel_ncs/idp /vobs/gsn_rel_sgsne/idp/idp_eps/idl /vobs/gsn_rel_sgsnw/idp/idp_ups/idl ${GSN_WS_ROOT}/sgsn_mme/sgsn-e/eps ${GSN_WS_ROOT}/sgsn_mme/sgsn-w/ups ${GSN_WS_ROOT}/sgsn_mme/sgsn-gt/mps ${GSN_WS_ROOT}/sgsn_mme/business_specific ${GSN_WS_ROOT}/sgsn_mme/capella/ncs /vobs/gsn_rel_gsn/idp /vobs/gsn_rel_ncs/idp /vobs/gsn_rel_sgsn/idp/idp_mps/idl /vobs/gsn_rel_sgsnw/idp/idp_ups/idl /vobs/gsn_rel_sgsne/idp/idp_eps/idl /vobs/gsn_rel_sgsne/idp/idp_ems/idl ${GSN_WS_ROOT}/sgsn_mme/test/gtt ${GSN_WS_ROOT}/sgsn_mme/cps/dpe/src ${GSN_WS_ROOT}/sgsn_mme/cps/os_extensions/src ${GSN_WS_ROOT}/sgsn_mme/oms -type f -name "*.[eh]rl" | sort | xargs etags -a --language=erlang --output=$HOME/.emacs-desktop/$CLEARSTART_VIEWTAG/platform/TAGS && find ${GSN_WS_ROOT}/cis/ ${GSN_WS_ROOT}/sgsn_mme/cps/ ${GSN_WS_ROOT}/sgsn_mme/capella/gss ${GSN_WS_ROOT}/sgsn_mme/capella/sds -type f -name "*.[ch]"  -o -type f -name "*.[cc][hh]" | sort | xargs etags -a --output=$HOME/.emacs-desktop/$CLEARSTART_VIEWTAG/platform/TAGS2'
alias dptags 'rm -rf $HOME/.emacs-desktop/$CLEARSTART_VIEWTAG/platform/TAGS $HOME/.emacs-desktop/$CLEARSTART_VIEWTAG/platform/TAGS2'
