# utl_print_program_code_above_output
Print program code above output.  Keywords: sas sql join merge big data analytics macros oracle teradata mysql sas communities stackoverflow statistics artificial inteligence AI Python R Java Javascript WPS Matlab SPSS Scala Perl C C# Excel MS Access JSON graphics maps NLP natural language processing machine learning igraph DOSUBL DOW loop stackoverflow SAS community.

    Print program code above output

    https://tinyurl.com/ybsr9gpv
    https://github.com/rogerjdeangelis/utl_print_program_code_above_output

    Poor mans SASweave
    https://tinyurl.com/ya2olly4
    https://github.com/rogerjdeangelis/utl_documenting_your_programs_with_a_poor_mans_jupiter_notebook_knitr_or_sasweave

    SAS  Forum
    https://tinyurl.com/y85z2khd
    https://communities.sas.com/t5/Base-SAS-Programming/Print-Syntax-Above-Output/m-p/476944

    This is just one way

    INPUT
    =====

      proc print data=sashelp.class;
      run;quit;

      EXAMPLE OUTPUT (in output window not log)
      -----------------------------------------

      proc print data=sashelp.class;
      run;quit;

      Obs    NAME       SEX    AGE    HEIGHT    WEIGHT

        1    Alfred      M      14     69.0      112.5
        2    Alice       F      13     56.5       84.0
        3    Barbara     F      13     65.3       98.0
        4    Carol       F      14     62.8      102.5
        5    Henry       M      14     63.5      102.5
        6    James       M      12     57.3       83.0



    PROCESS  (one of the few advantages of 'call execute', delays execution)
    =======

    options formdlim=" ";
    data _null_;
      input lyn $80.;
      file print;
      put lyn;
      call execute(lyn);
    cards4;
    proc print data=sashelp.class;
    run;quit;
    ;;;;
    run;quit;


    OUTPUT
    ======

    proc print data=sashelp.class;
    run;quit;

    Obs    NAME       SEX    AGE    HEIGHT    WEIGHT

      1    Alfred      M      14     69.0      112.5
      2    Alice       F      13     56.5       84.0
      3    Barbara     F      13     65.3       98.0
      4    Carol       F      14     62.8      102.5
      5    Henry       M      14     63.5      102.5
      6    James       M      12     57.3       83.0
      7    Jane        F      12     59.8       84.5
      8    Janet       F      15     62.5      112.5
      9    Jeffrey     M      13     62.5       84.0
     10    John        M      12     59.0       99.5
     11    Joyce       F      11     51.3       50.5
     12    Judy        F      14     64.3       90.0
     13    Louise      F      12     56.3       77.0
     14    Mary        F      15     66.5      112.0
     15    Philip      M      16     72.0      150.0
     16    Robert      M      12     64.8      128.0
     17    Ronald      M      15     67.0      133.0
     18    Thomas      M      11     57.5       85.0
     19    William     M      15     66.5      112.0

    *                _              _       _
     _ __ ___   __ _| | _____    __| | __ _| |_ __ _
    | '_ ` _ \ / _` | |/ / _ \  / _` |/ _` | __/ _` |
    | | | | | | (_| |   <  __/ | (_| | (_| | || (_| |
    |_| |_| |_|\__,_|_|\_\___|  \__,_|\__,_|\__\__,_|

    ;

      data is self contained in the only datastep

    *          _       _   _
     ___  ___ | |_   _| |_(_) ___  _ __
    / __|/ _ \| | | | | __| |/ _ \| '_ \
    \__ \ (_) | | |_| | |_| | (_) | | | |
    |___/\___/|_|\__,_|\__|_|\___/|_| |_|

    ;

    see process;
