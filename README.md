# http-filters
##<filter>
##	<filter-name>httpHeaderSecurity</filter-name>
##  <filter-class>com.vteam.soter.web.filters.HttpHeaderSecurityFilter</filter-class>
##	<init-param>
##		<param-name>antiClickJackingOption</param-name>
##		<param-value>SAMEORIGIN</param-value>
##	</init-param>
##</filter>
##
##<filter-mapping>
##	<filter-name>httpHeaderSecurity</filter-name>
##	<url-pattern>/*</url-pattern>
##	<dispatcher>REQUEST</dispatcher>
##</filter-mapping>
