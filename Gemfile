# Declare your gem's dependencies in manageiq-providers-azure_stack.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# Load Gemfile with dependencies from manageiq
eval_gemfile(File.expand_path("spec/manageiq/Gemfile", __dir__))

# github 'kbrock/azure-sdk-for-ruby', branch: 'v2021-smaller' do
BR='require_relative' # 'v2021-smaller'
  gem 'azure_mgmt_compute',   github: 'kbrock/azure-sdk-for-ruby', branch: BR, :glob => 'management/azure_mgmt_compute/azure_mgmt_compute.gemspec'
  gem 'azure_mgmt_monitor',   github: 'kbrock/azure-sdk-for-ruby', branch: BR, :glob => 'management/azure_mgmt_monitor/azure_mgmt_monitor.gemspec'
  gem 'azure_mgmt_network',   github: 'kbrock/azure-sdk-for-ruby', branch: BR, :glob => 'management/azure_mgmt_network/azure_mgmt_network.gemspec'
  gem 'azure_mgmt_resources', github: 'kbrock/azure-sdk-for-ruby', branch: BR, :glob => 'management/azure_mgmt_resources/azure_mgmt_resources.gemspec'
  gem 'ms_rest_azure',        github: 'kbrock/azure-sdk-for-ruby', branch: BR, :glob => 'runtime/ms_rest_azure/ms_rest_azure.gemspec'
# end
