# README

FREEDOC PROJECT

This project aims at creating a relational database for the Gossip Project.

To feed this database, please type the following commands in your Terminal (in the right order) :
	- $rails db:migrate VERSION=0
	- $rails db:migrate
	- $rails db:seed

To test the relations between the tables, you could try the following entries in the rails console ($rails c).

	- User.find(3).gossips
	- User.find(2).received_messages
	- User.find(8).sent_messages

