AUTOMAKE_OPTIONS = foreign

bin_PROGRAMS = simulator simdebug

simulator_SOURCES = 				 		 	 \
					coresim/main.cpp 			 \
					coresim/debug.cpp 			 \
					coresim/node.cpp 			 \
					coresim/queue.cpp 			 \
					coresim/packet.cpp 		 	 \
					coresim/event.cpp 			 \
					coresim/topology.cpp 		 \
					coresim/flow.cpp 			 \
					coresim/random_variable.cpp  \
					ext/factory.cpp 		 	 \
					ext/pfabricqueue.cpp         \
					ext/pfabricflow.cpp          \
					ext/schedulinghost.cpp	     \
					ext/fountainflow.cpp 	   	 \
					ext/capabilityflow.cpp 	   	 \
					ext/capabilitypredictionflow.cpp   \
					ext/capabilityhost.cpp 	   	 \
					ext/fastpassflow.cpp 	   	 \
					ext/fastpasspredictionflow.cpp     \
					ext/fastpasshost.cpp 	   	 \
					ext/fastpassTopology.cpp	 \
					ext/fifoflow.cpp	 		 \
					ext/pfabricpredictionflow.cpp \
					ext/pfabricaging.cpp           \
					ext/tcpflow.cpp				 \
					ext/dctcpQueue.cpp			 \
					ext/dctcpFlow.cpp			 \
					run/params.cpp 		 	 	 \
					run/stats.cpp 			   	 \
                    run/trace_cdf_generator.cpp \
					run/experiment.cpp 

simulator_CXXFLAGS = -g -O3 -gdwarf-2 -Wall -std=c++0x 

simdebug_SOURCES = $(simulator_SOURCES)

simdebug_CXXFLAGS  = -g -O0 -gdwarf-2 -Wall -std=c++0x 

#CFLAGS = -g -O3 -gdwarf-2 -Wall -std=c++0x 
#CXXFLAGS = -g -O3 -gdwarf-2 -Wall -std=c++0x 

