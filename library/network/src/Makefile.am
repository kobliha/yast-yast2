# Sources for yast2

module_DATA = \
  modules/PortAliases.rb \
  modules/SuSEFirewall.rb \
  modules/NetworkConfig.rb \
  modules/Internet.rb \
  modules/SuSEFirewallProposal.rb \
  modules/PortRanges.rb \
  modules/NetworkInterfaces.rb \
  modules/CWMFirewallInterfaces.rb \
  modules/NetworkPopup.rb \
  modules/NetworkService.rb \
  modules/SuSEFirewallExpertRules.rb \
  modules/SuSEFirewallServices.rb \
  modules/SLPAPI.pm \
  modules/DnsServerAPI.pm

scrconf_DATA = \
  scrconf/sysconfig_SuSEfirewall2.scr \
  scrconf/net_showexports.scr \
  scrconf/network.scr

agent_SCRIPTS = \
  servers_non_y2/ag_showexports

ylibdir = @ylibdir@/network
ylib_DATA = \
  lib/network/firewalld.rb \
  lib/network/susefirewall.rb \
  lib/network/susefirewall2.rb \
  lib/network/susefirewalld.rb \
  lib/network/susefirewallservices.rb \
  lib/network/susefirewall2services.rb \
  lib/network/susefirewalldservices.rb

yfwlibdir = @ylibdir@/y2firewall
yfwlib_DATA = \
  lib/y2firewall/firewalld.rb

yfwdlibdir = @ylibdir@/y2firewall/firewalld
yfwdlib_DATA = \
  lib/y2firewall/firewalld/api.rb


EXTRA_DIST = $(module_DATA) $(scrconf_DATA) $(agent_SCRIPTS) $(ylib_DATA) $(yfwlib_DATA) $(yfwdlibdir_DATA)

include $(top_srcdir)/Makefile.am.common
