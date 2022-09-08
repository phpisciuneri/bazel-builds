genrule(
    name = "clp",
    outs = ["hello20s.txt"],
    cmd_bash = """
      wget https://raw.githubusercontent.com/coin-or/coinbrew/master/coinbrew
      chmod u+x coinbrew
     ./coinbrew fetch Clp@master
     ./coinbrew build Clp
    """,
)
