require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "ruby-password"
    gem.summary = %Q{A password handling library for Ruby with interface to CrackLib}
    gem.description = %Q{Ruby/Password is a suite of password handling methods for Ruby. It supports
the manual entry of passwords from the keyboard in both buffered and
unbuffered modes, password strength checking, random password generation,
phonemic password generation (for easy memorisation by human-beings) and the
encryption of passwords.}
    gem.email = "crazymykl@gmail.com"
    gem.homepage = "http://github.com/crazymykl/ruby-password"
    gem.authors = ["Albert Lash", "Ian Macdonald", "Mike MacDonald"]
    gem.add_dependency "ruby-termios"
    gem.add_development_dependency "shoulda"
    gem.extensions = FileList['extconf.rb']
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end

