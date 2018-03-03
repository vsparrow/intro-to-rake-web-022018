namespace :db do
  desc 'environemnt task'
  task :environment do
    require_relative './config/environment'
  end
  desc 'migrate database'
  task :migrate => :environment do
    Student.create_table
  end
  desc 'create seed files for database'
  task :seed do
    require_relative './db/seeds.rb'
  end
end



namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end
  desc 'outputs hola to the terminal'
  task :hola do
    puts "hola de Rake!"
  end
end
